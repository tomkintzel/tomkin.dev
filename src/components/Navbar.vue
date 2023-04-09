<script lang="ts" setup>

</script>

<template>
  <header flex justify-between items-center class="mx-5 my-4">
    <div>
      <RouterLink to="/">
        <Icon icon-base />
      </RouterLink>
    </div>
    <nav flex gap-2 items-center>
      <a
        icon-btn i-carbon-logo-github
        rel="noreferrer"
        href="https://github.com/tomkintzel"
        target="_blank"
        title="GitHub"
        class="dark:hover:text-white hover:text-gray-200"
      />
      <a
        rel="noreferrer"
        href="https://twitter.com/tomkin_dev"
        target="_blank"
        icon-btn i-carbon-logo-twitter
        class="dark:hover:text-white hover:text-gray-200"
      />
      <a
        rel="noreferrer"
        href="https://instagram.com/tomkin_dev"
        target="_blank"
        icon-btn i-carbon-logo-instagram
        class="dark:hover:text-white hover:text-gray-200"
      />
      <button icon-btn @click="toggleDark()">
        <div dark:i-carbon-moon i-carbon-sun />
      </button>
    </nav>
  </header>
</template>
