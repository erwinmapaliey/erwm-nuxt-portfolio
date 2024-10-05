<template>
  <ul class="flex flex-col gap-2">
    <li>
      <NuxtLink to="#about" class="menu-link">ABOUT</NuxtLink>
    </li>
    <li>
      <NuxtLink to="#experience" class="menu-link">EXPERIENCE</NuxtLink>
    </li>
    <li>
      <NuxtLink to="#projects" class="menu-link">PROJECTS</NuxtLink>
    </li>
  </ul>
</template>

<style scoped>
.menu-link {
  @apply text-sm hover:text-gray-500 hover:ml-4
}
</style>