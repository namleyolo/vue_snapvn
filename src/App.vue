<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Index test="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Index from './components/index/Index.vue'
import data from '@/data'
  console.log("data:::",data);

export default {
  name: 'app',
  components: {
    Index
  },
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
