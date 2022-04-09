<template>
  <div class="container mx-auto px-10 md:px-0">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <div></div>
      <div>
        <div class="mt-10">
          <h1 class="text-5xl font-semibold text-gray-600">Todo List</h1>

          <div class="mt-6">
            <form>
              <div class="grid grid-cols-1 gap-4">
                <div>
                  <input class="border-2 outline-none py-2 px-2 shadow-md font-medium w-full rounded border-blue-300 hover:border-blue-600 focus:border-blue-600 focus:shadow-blue-200" />
                </div>
                <div>
                  <div class="grid grid-cols-2 gap-2">
                    <div>
                      <button class="text-white py-2 px-4 shadow-md w-full rounded bg-red-400 hover:bg-red-600 font-semibold">Remove All Todos</button>
                    </div>
                    <div>
                      <button class="text-white py-2 px-4 shadow-md w-full rounded bg-blue-400 hover:bg-blue-600 font-semibold">Add Todo</button>
                    </div>
                  </div>
                </div>
              </div>
            </form>
          </div>

          <div class="mt-8 text-center">
            <div id="todoList">
              <div class="grid grid-cols-1 gap-3">
                <div>
                  <div class="h-full">
                    <p class="text-gray-400">It appears you didn't added any To-Do.</p>
                  </div>
                </div>
                <div class="rounded shadow-md p-3 h-full hover:shadow-gray-400 text-gray-600 text-lg font-semibold completed">
                  <span class="text-gray-600 text-lg font-semibold">Complete Homework</span>
                </div>
                <div class="rounded shadow-md p-3 h-full hover:shadow-gray-400 text-gray-600 text-lg font-semibold">
                  <span>Riding Bicycle</span>
                </div>
              </div>
            </div>
          </div>

        </div>
      </div>
      <div></div>
    </div>
  </div>
</template>

<script setup>
</script>

<style>
  .completed {
    text-decoration: line-through;
  }
</style>
