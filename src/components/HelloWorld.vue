<template>
  <div class="hello flex justify-center">
    <h1 class="flex">Rocklin Disc Golf Course</h1>
    <h2>- Coming soon -</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  background-color: rgba(255, 255, 255, .8);
  padding: .5rem 0;
}
h1 {
  margin-bottom:0;
}
h2 {
  margin-top:0.5rem;
}
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
