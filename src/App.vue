<template>
  <div id="app">
    <KeyValuePair />
  </div>
</template>

<script>
import KeyValuePair from './components/KeyValuePair.vue'

export default {
  name: 'app',
  components: {
    KeyValuePair
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
