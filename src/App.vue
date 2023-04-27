<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Sectionblu from './components/SectionBlu.vue'
import Footer from "./components/Footer.vue"
export default {
  name: "App",
  
  components:{
    Header,
    Main,
    Sectionblu,
    Footer
  }
}
</script>

<template>
  <div>
    <Header/>
    <Main/>
    <sectionblu/>
    <Footer/>
  </div>
</template>

<style lang="scss">

@use "./scss/main.scss";

</style>
