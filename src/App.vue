<script setup lang="ts">
const msg = $ref('hello varlet!')
</script>

<template>
  <div class="app-container">
    <var-button type="primary">{{ msg }}</var-button>
  </div>
</template>

<style lang="less">
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}

.app-container {
  padding: 20px;
  min-height: 100vh;
  background: #fff;
}
</style>
