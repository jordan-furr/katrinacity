<template>
  <div class="fixed top-0 left-0 right-0 bottom-0">
    <k-header/>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'katrinacity',
  meta: [
    { name: 'katrinacity', content: 'Katrina Stalcup' }
  ],
  bodyAttrs: {
    class: 'test'
  }
})
</script>