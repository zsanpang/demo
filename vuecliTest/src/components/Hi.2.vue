<template>
  <div class="hello">
    <h3>{{ msg }}</h3>
    <h4>传值：{{ $route.params.username }}</h4>
  </div>
</template>

<script>
export default {
  name: 'HI',
  data () {
    return {
      msg: 'I am HI Page!2'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
