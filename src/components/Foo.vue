<template>
  {{ foo }}
</template>

<script setup lang="ts">
defineProps<{
  foo: number;
}>();
</script>
