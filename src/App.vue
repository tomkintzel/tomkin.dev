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
  <main font-sans class="mx-5 my-10 py-10 md:m-auto">
    <RouterView />
  </main>
</template>
