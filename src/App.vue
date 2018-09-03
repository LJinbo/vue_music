<template>
  <div id="app">
    <headers></headers>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
import Headers from "./components/Hader/Hader";
  export default {
    name: 'App',
    components: {
      Headers,
    }
  }
</script>

<style lang="scss">
</style>
