<template>
  <div id="app">
    <router-view :key="$route.fullPath" />
  </div>
</template>

<style lang="scss">

  #app {
    height: 100%;
    width: 100%;
  }
</style>
