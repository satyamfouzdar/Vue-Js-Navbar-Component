<template>
  <div id="app">
    <NavigationTopSticky />
  </div>
</template>

<script>
import NavigationTopSticky from './components/NavigationTopSticky.vue'

export default {
  name: 'App',
  components: {
    NavigationTopSticky
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
