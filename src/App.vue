<template>
  <div id="app">
    <ComingSoon />
  </div>
</template>

<script>
import ComingSoon from './components/ComingSoon.vue'

export default {
  name: 'App',
  components: {
    ComingSoon
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  height: 100%;
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  justify-content: space-between;
}

body{
  display: flex;
  flex-direction: column;
  height: 100%;
}

main{
  display:flex;
  flex-direction:column;
  width: 100%;
}
</style>
