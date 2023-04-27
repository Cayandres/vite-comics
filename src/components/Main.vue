<script>
export default {
  name:'Main'
  
}
</script>

<template>
  <main>
    <div class="container"><span>content goes here</span></div>
  </main>
</template>

<style lang="scss" scoped>
@use "../scss/general/mixin" as*;
  main{
    background-color: black;
    div{
    @include centerFlex('both');
    color: white;
    height: 100px;
  }
  }
 
</style>