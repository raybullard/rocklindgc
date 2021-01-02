<template>
  <div class="hello static">
    <div class="container mx-auto">
      <img class="flex w-40 h-40 float-left mr-8 object-left-top relative bottom-10" src="../../public/assets/Rocklin_DGC_logo.png" alt="Rocklin DGC logo" />
      <h1 class="flex text-5xl font-bold text-gray-800">Rocklin Disc Golf Course</h1>
      <h2 class="flex text-2xl">- Coming soon -</h2>
    </div>
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
</style>
