<script lang="ts" setup>
useHead({
  title: 'tomkin.dev | Tom Kintzel, Web Entwickler',
  meta: [
    { name: 'description', content: 'Hello World' },
  ],
})
</script>

<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
    <RouterView />
    <TheFooter />
  </main>
</template>
