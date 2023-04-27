<script>
export default {
  name:'Main'
  
}
</script>

<template>
  <div><span>content goes here</span></div>
</template>

<style lang="scss" scoped>
@use "../scss/general/mixin" as*;

  div{
    @include centerFlex('both');
    color: white;
    height: 100px;
    background-color: black;
  }
</style>