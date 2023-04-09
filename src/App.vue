<script lang="ts" setup>
useHead({
  title: 'tomkin.dev | Tom Kintzel, Web Entwickler',
  meta: [
    { name: 'description', content: 'Hello World' },
  ],
})
</script>

<template>
  <Navbar />
  <main font-sans text="gray-700 dark:gray-200" mx-5 my-10 md:m-36>
    <RouterView />
  </main>
</template>
