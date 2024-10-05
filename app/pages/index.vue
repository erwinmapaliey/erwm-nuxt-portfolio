<template>
  <div class="flex flex-col gap-10">
    <section id="about">
      <about />
    </section>
    <section id="experience">
      <ExperiencePage />
    </section>
    <section id="projects">
      <ProjectPage />
    </section>
  </div>
  
</template>

<script setup>
import about from './about.vue';
</script>