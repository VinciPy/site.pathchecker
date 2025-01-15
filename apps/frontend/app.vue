<script setup>
</script>

<template>
  <UContainer class="border-solid border-black rounded-full md:pt-4 bg-gray-400/5 my-4" :ui="{ container: 'bg-gray-400/5 md:rounded-full border-b md:border dark:border-gray-800' }">
      <h1 class="font-bold text-black dark:text-white">
        Site Pather Checker
      </h1>
      <UColorModeButton />
      <UButton to="https://github.com/atinux/nuxt-deno-kv" target="_blank" icon="i-simple-icons-github" color="gray" variant="ghost" />
  </UContainer>
  <UContainer>
    <UMain>
      <NuxtPage />
    </UMain>
  </UContainer>
  <UContainer class="md:pb-4" :ui="{ bottom: { container: 'bg-gray-400/5 md:rounded-full border-t md:border dark:border-gray-800' } }">
      Published under MIT License.
      <UButton to="https://x.com/Atinux" target="_blank" icon="i-simple-icons-x" color="gray" variant="ghost" />
      <UButton to="https://github.com/atinux/nuxt-deno-kv" target="_blank" icon="i-simple-icons-github" color="gray" variant="ghost" />
  </UContainer>
  <UNotifications />
</template>