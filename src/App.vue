<template>
  <div id="app">
    <!--  给router-link展示的区域↓  -->
    <router-view/>
  </div>
</template>

<style lang="scss" scoped>
#app {
  height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

#icp {
  position: fixed;
  text-align: center;
  bottom: 10px;
  margin: 0 auto;
  width: 100%;
  color: #637e8f
}
</style>
