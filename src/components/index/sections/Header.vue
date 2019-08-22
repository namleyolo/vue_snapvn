<template>
  <div class="container">
      <p>Header</p>
      <p>Nuber corect:: {{numCorrect}} /  {{numTotal}}</p>
      <div class="columns">
          <div class="column is-6 is mobile">
              test 6
          </div>
          <div class="column is-6 is mobile">
            test 6 right
          </div>
      </div>
  </div>
</template>

<script>

export default {
  props: [
      'numCorrect',
      'numTotal'
  ],
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
