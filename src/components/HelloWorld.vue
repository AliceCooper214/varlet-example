<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <h2>{{ msg }}</h2>

  <p>
    See
    <code>README.md</code>
    for more information.
  </p>

  <p>
    <a href="https://varlet.gitee.io/varlet-ui/#/en-US/home" target="_blank">Varlet Docs</a>
    <span>|</span>
    <a href="https://v3.vuejs.org/" target="_blank">Vue3 Docs</a>
  </p>
</template>

<style scoped>
h2 {
  text-align: center;
}

a {
  color: #3a7afe;
}

span {
  margin: 0 10px;
  color: #3a7afe;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
