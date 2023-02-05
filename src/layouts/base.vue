<template>
  <Foo :foo="Math.random()" client:load />
  <slot />
</template>

<script setup lang="ts">
const page = usePage();
</script>
