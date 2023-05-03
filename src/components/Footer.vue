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
            <h2>DC COMMICS</h2>
            <ul>
             <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
          </nav>
          <nav>
            <h2>SHOP</h2>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC COLLECTIBLES</a></li>
            </ul>       
          </nav>
        </div>
        <div class="col">
          <nav>
            <h2>DC</h2>
            <ul>
               <li><a href="#">Term Of Use</a></li>
               <li><a href="#">Privacy Policy(NEW)</a></li>
               <li><a href="#">Ad Choices</a></li>
               <li><a href="#">Advertising</a></li>
               <li><a href="#">Jobs</a></li>
               <li><a href="#">Subscriptions</a></li>
               <li><a href="#">Talent Workshop</a></li>
               <li><a href="#">CPSC Certificates</a></li>
               <li><a href="#">Ratings</a></li>
               <li><a href="#">Shop help</a></li>
               <li><a href="#">Contact Us</a></li>
            </ul>
          </nav>
        </div>
        <div class="col">
          <nav>
            <h2>SITES</h2>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kinds</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </nav>
        </div>
  
      </div>
      <div class="image">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
    
  </div>
  <div class="footer-social">
    <div class="footer down container">
      <button>SING-UP NOW!</button>
      <div class="social">
        <h4>FOLLOW US</h4>
        <ul>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
        </ul>
      </div>


    </div>
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
      margin: 30px 0;
      nav{
        padding: 20px 30px 0 0;
      }
      h2{
        padding-bottom: 25px;
        color: white;
      }
      ul{
        line-height: 25px;
      }
      a{
        color: gray;
        &:hover{
          color: $primary-color;
        }
      }
    }
    
  
    .image{
      width: 50%;
      min-height: 100px;
      position: relative;
      overflow: hidden;
      img{
        position: absolute;
        bottom: -40px;
        height: 550px;
        width: 100%;
      }
    }
  }

  .footer-social{
    height: 100px;
    background-color: #303030;
    .footer.down{
      height: 100%;
      @include beetweenAround('beetween');
      align-items: center;
      button{
        padding: 10px;
        background-color: #303030;
        border: 1px solid $primary-color;
        color:white
      }
      .social{
        color: white;
        display: flex;
        align-items: center;
        h4{
          color: $primary-color;
          padding-right: 15px;
        }
        ul{
          display: flex;  
        }
      }
    }
  }

}



</style>