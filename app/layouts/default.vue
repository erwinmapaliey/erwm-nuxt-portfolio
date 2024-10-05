<template>
  <div class="container mx-auto flex justify-between gap-4 max-w-7xl">
    <header class="sticky top-0 flex max-h-screen w-1/2 flex-col justify-between py-24">
      <div>
        <NuxtLink to="/" class="text-4xl sm:text-5xl font-bold">Erwin Mapaliey</NuxtLink>
        <h3 class="text-xl mt-4">Senior Software Engineer</h3>
        <MenuItem class="mt-12" />
      </div>
      <div>
        <SocialMediaList />
      </div>
    </header>
    <main class="w-1/2 py-12">
      <slot />
    </main>
  </div>
</template>

<script setup>
useHead({
  titleTemplate: 'Erwin Mapaliey',
  link: [
    {
      rel: 'preconnect',
      href: 'https://fonts.googleapis.com'
    },
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap',
      crossorigin: ''
    }
  ]
})
</script>

<style>
body {
  font-family: 'Inter';
}
body {
  @apply bg-gray-900 text-slate-300
}
</style>