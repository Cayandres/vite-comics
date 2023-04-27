<script>
import Header from "./components/Header.vue"
export default {
  name: "App",
  
  components:{
    Header,
  }
}
</script>

<template>
  <div class="container">
    <Header/>
    <h1>ciao</h1>
  </div>
</template>

<style lang="scss">

@use "./scss/main.scss";

</style>
