<template>
  <ul class="flex gap-4">
    <li>
      <NuxtLink to="https://instagram.com/erwinmapaliey" target="_blank"><font-awesome :icon="faInstagram" class="text-2xl" /></NuxtLink>
    </li>
    <li>
      <NuxtLink to="https://www.linkedin.com/in/erwinmapaliey/" target="_blank"><font-awesome :icon="faLinkedin" class="text-2xl" /></NuxtLink>
    </li>
    <li>
      <NuxtLink to="https://github.com/erwinmapaliey" target="_blank"><font-awesome :icon="faGithub" class="text-2xl" /></NuxtLink>
    </li>
  </ul>
</template>

<script setup>
import { faGithub, faInstagram, faLinkedin } from '@fortawesome/free-brands-svg-icons'
</script>