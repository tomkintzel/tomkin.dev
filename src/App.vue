<script lang="ts" setup>
useHead({
  title: 'tomkin.dev | Tom Kintzel, Web Entwickler',
  meta: [
    { name: 'description', content: 'Hello World' },
  ],
})
</script>

<template>
  <main font-sans text="center gray-700 dark:gray-200">
    <Navbar />
    <RouterView />
    <TheFooter />
  </main>
</template>
