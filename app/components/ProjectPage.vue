<template>
  <div>
    <h2 class="text-sm mb-8 font-semibold">PROJECTS</h2>
    <div v-for="n in 5">
      <div class="font-light grid grid-cols-6 mb-4">
        <div class="col-span-2 p-4">
          <img src="/images/contoh.jpg" width="150">
        </div>
        <div class="col-span-4 p-2">
          <div class="text-white mb-2 font-normal">Judul Project</div>
          <div class="text-gray-400 text-sm mb-2">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum consequuntur sunt eius necessitatibus possimus repudiandae, molestias placeat est eum voluptatem!</div>
          <div class="flex gap-2">
            <div v-for="n in 4" class="bg-teal-950 text-teal-200 rounded-full text-xs flex items-center px-4 py-1">
              PHP
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>