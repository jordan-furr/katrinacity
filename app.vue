<template>
  <div class="fixed top-0 left-0 right-0 bottom-0">
    <k-header/>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Damian City',
  meta: [
    { name: 'Damian City', content: 'Damian Stalcup' }
  ],
  bodyAttrs: {
    class: 'test'
  }
})
</script>