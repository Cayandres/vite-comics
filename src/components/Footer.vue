<script>
export default {
  name: 'Footer'
}
</script>

<template>
  <footer>
    <div class="container">
      <div class="footer up">
      <div class="link-list">
        <div class="col">
          <nav>
            <h4>DC COMMICS</h4>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
          </nav>
          <nav>
            <h4>Dc</h4>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>           
          </nav>
        </div>
        <div class="col">
          <nav>
            <h4>DC COMMICS</h4>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
          </nav>
        </div>
        <div class="col">
          <nav>
            <h4>DC COMMICS</h4>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
            <ul><li><a href="#">1</a></li></ul>
          </nav>
        </div>
  
      </div>
      <div class="image">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
    <div class="footer down"></div>

    </div>
  </footer>
 
</template>

<style lang="scss" scoped>
@use '../scss/general/mixin' as*;
@use '../scss/general/variables' as*;

footer{
  background-image: url(../assets/img/footer-bg.jpg);
  .footer.up{
    display: flex;
    min-height: 250px;
    .link-list{
      display: flex;
      width: 55%;
    }
  
    .image{
      width: 45%;
      min-height: 100px;
      position: relative;
      overflow: hidden;
      img{
        position: absolute;
        bottom: -40px;
        height: 350px;
        
        
      }
    }
  }

}



</style>