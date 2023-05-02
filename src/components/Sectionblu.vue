<script>
export default {
  name:'Sectionblu',
}
</script>

<template>
  <nav>
    <ul class="container">
      <li>
        <div class="img">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        </div>
        <a href="">DIGITAL COMICS</a>
      </li>
      <li>
        <div class="img">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
        </div>
        <a href="">DC MERCHANDISE</a>
      </li>
      <li>
        <div class="img">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        </div>
        <a href="">SUSCRIPTION</a>
      </li>
      <li>
        <div class="img">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        </div>
        <a href="">COMIC SHOP LOCATOR</a>
      </li>
      <li>
        <div class="img">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        </div>
        <a href="">DC POWER VISA</a>
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
      cursor: pointer;
      height: 40px;
      @include centerFlex("both");
      a{
        color: white;
      }
      // padding: 0 40px;
      .img{
        width: 35px;
        height: 40px;
        margin-right: 15px;
        img{
          width: 100%;
          height: 100%;
        }
      }

    }
      

  }
}
</style>