<template>
  <div class="container">
      <p>Yolo</p>
      <Header :numCorrect="numCorrect" :numTotal="numTotal" />
  </div>
</template>

<script>


import Header from './sections/Header.vue' ;


export default {
  name: 'Index',
  components: {
    Header
  },
  data() {
    return {
      numCorrect:0,
      numTotal : 0
    }
  },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
