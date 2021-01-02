<template>
  <div class="hello static">
    <div class="container mx-auto">
      <img class="flex w-24 h-24 ml-2 sm:ml-0 sm:w-40 sm:h-40 sm:float-left mr-8 sm:object-left-top sm:relative bottom-10" src="../../public/assets/Rocklin_DGC_logo.png" alt="Rocklin DGC logo" />
      <h1 class="flex ml-2 sm:ml-0 text-2xl sm:text-4xl font-bold text-gray-800">Rocklin Disc Golf Course</h1>
      <h2 class="flex text-1xl sm:text-2xl">- Coming soon -</h2>
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
