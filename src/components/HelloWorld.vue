<template>
  <h1>{{ msg }}</h1>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">Vite Documentation</a> |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button class="btn-primary" @click="count++">count is: {{ count }}</button>
  <p class="bg-red">
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
  
</template>

<script >

  export default {
    props: {
      msg: String,
    },
    data() {
      return {
        count: 0,
      }
    },
  };

</script>


<style lang="scss">

  

  a {
    color: #42b983;
  }
</style>