<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myTitle /> 
    <myJumbo />
  </div>
</template>

<script>
import myTitle from './components/myTitle.vue'
import myJumbo from './components/hero.vue'
export default {
  name: 'App',
  components: {
    myTitle,
    myJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>