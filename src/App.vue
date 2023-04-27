<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import SectionBlu1 from './components/SectionBlu.vue'
import Sectionblu from "./components/Sectionblu.vue"
export default {
  name: "App",
  
  components:{
    Header,
    Main,
    Sectionblu,
    SectionBlu1
  }
}
</script>

<template>
  <div class="container">
    <Header/>
    <Main/>
    <sectionblu/>
    <h1>ciao</h1>
  </div>
</template>

<style lang="scss">

@use "./scss/main.scss";

</style>
