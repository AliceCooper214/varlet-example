<script setup lang="ts">
const msg = $ref('hello varlet!')
</script>

<template>
  <var-button type="primary">{{ msg }}</var-button>
</template>
