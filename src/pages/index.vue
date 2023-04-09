<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})

const name = $ref('')

const router = useRouter()
function go() {
  if (name)
    router.push(`/hi/${encodeURIComponent(name)}`)
}
</script>

<template>
  <div>
    <h1 text="3xl">
      Tom Kintzel.
    </h1>
  </div>
</template>
