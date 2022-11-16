<script setup lang="ts">
function handleClick() {
  Snackbar('Hello')
}
</script>

<template>
  <var-button @click="handleClick">Say Hello</var-button>
</template>

<style>
body {
  transition: background-color .25s, color .25s;
  color: var(--color-text);
  background-color: var(--color-body);
}
</style>
