<template>
  <div class="app-container">
    <div class="project-container">
      <img class="logo" src="./assets/logo.png" alt="logo" />
      <div class="name">VARLET</div>
    </div>
    <hello-world msg="Material design mobile component library for Vue3" />
  </div>
</template>

<style lang="less">
@keyframes fade-in {
  from {
    transform: scale(0.9);
    opacity: .1;
  }

  to {
    transform: scale(1);
    opacity: 1;
  }
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}

.app-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  animation: fade-in 1s forwards;

  .project-container {
    display: flex;
    align-items: center;

    .logo {
      width: 36px;
      margin-right: 16px;
    }

    .name {
      font-size: 32px;
      color: #555;
    }
  }
}
</style>
