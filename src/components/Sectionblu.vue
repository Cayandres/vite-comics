<script>
export default {
  name:'Sectionblu',
}
</script>

<template>
  <nav>
    <ul>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="">1</a>
      </li>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="">1</a>
      </li>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="">1</a>
      </li>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="">1</a>
      </li>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="">1</a>
      </li>

    </ul>
  </nav>
</template>

<style lang="scss" scoped>
@use '../scss/general/variables' as*;
@use '../scss/general/mixin' as*;
nav{
  @include centerFlex("both");
  min-height: 100px;
  background-color: $primary-color;
  ul{
    @include beetweenAround("evenly");
    li{
      padding: 0 40px;
      img{
      width: 40%;
     }

    }
      

  }
}
</style>