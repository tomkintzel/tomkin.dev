<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div class="m-auto about">
    <h1 text="4xl" class="opacity-100" fw-bold>
      Tom Kintzel.
    </h1>
    <span class="opacity-60" flex gap-2 items-center>Web-Entwickler aus Bielefeld, <div i-flag-de-4x3 /></span>
    <div class="mt-15">
      <p class="mb">
        Hey Leute, ich bin ein Webentwickler aus Bielefeld und arbeite bei der <a href="https://ecommerce-werkstatt.de" target="_blank" rel="noopener">ECW</a>. <br> Meine große Leidenschaft ist die Webentwicklung mit <a href="https://vuejs.org/">Vue</a> und dessen Ecosystem.
      </p>
      <p mb>
        Ich bin immer auf der Suche nach neuen Herausforderungen und liebe es, komplexe Probleme zu lösen und innovative Lösungen zu entwickeln.
      </p>
      <p class="mb">
        Vue ist einfach der Hammer, ich liebe die Flexibilität und Skalierbarkeit, die es bietet. Es ermöglicht es mir, Anwendungen schnell und einfach zu erstellen, ohne Kompromisse bei der Qualität einzugehen.
      </p>
      <p mb>
        Ich denke, das Beste an der Webentwicklung ist, dass man immer etwas Neues lernen und sich weiterentwickeln kann. Es ist so erfüllend, zu sehen, wie meine Arbeit dazu beiträgt, die Benutzererfahrung zu verbessern und die Effizienz zu steigern.
      </p>
      <p mb>
        Wenn ich nicht gerade vor meinem Computer sitze und Code schreibe, verbringe ich meine Zeit gerne mit Freunden oder mache Sport. Aber ich muss zugeben, dass ich immer wieder gerne zurück zum Entwickeln gehe - es ist einfach meine große Leidenschaft!
      </p>
    </div>
  </div>
</template>

<style scoped>
.about {
  max-width: 65ch;
  line-height: 1.75;
}

.about a {
  opacity: 1;
  color: #000;
  font-weight: bold;
}

.dark .about a {
  color: #fff;
}
</style>
