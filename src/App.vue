<template>
  <div class="varlet">
    <img alt="Varlet logo" src="./assets/logo.png" />
    <div class="varlet-name">VARLET</div>
  </div>
  <HelloWorld msg="Material design mobile component library for Vue3" />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.varlet {
  display: flex;
  align-items: center;
  justify-content: center;
}

.varlet > img {
  height: 60px;
  width: 60px;
  margin-right: 20px;
}

.varlet-name {
  font-size: 60px;
  font-family: Roboto;
}
</style>
