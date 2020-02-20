<template>
  <div id="app">
    <aa></aa>
    <bb></bb>
  </div>
</template>

<script>
import aa from './components/aa.vue'
import bb from './components/bb.vue'

export default {
  name: 'App',
  components: {
    aa,
    bb
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
  margin-top: 60px;
}
</style>
