<script>
import  dcList  from '../data/dc-comics.json'
import  ProducCard  from './partials/ProductCard.vue'
export default {
  name:'Main',
  components:{
    ProducCard
  },
  props:{

  },
  data() {
    return{
     dcList
    }
  },
  mounted(){
    console.log(this.dcList);
  }
  
}
</script>

<template>
  <main>
    <div class="jumbotron">
      <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
    <div class="container-background">
      <div class="container">
        <span>CURRENT SERIES</span>
        <ProducCard 
        v-for="(comic, index) in dcList"
        :key="index"
        :image="comic.thumb"
        :productName="comic.series"/>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use "../scss/general/mixin" as*;
@use "../scss/general/variables" as*;
  main{
    .jumbotron{
      height: 400px;
      position: relative;

      img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
      }
    }
    .container-background{
      background-color: black;
      color: white;

      .container{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        padding-top: 80px;
        span{
          font-size: 30px;
          font-weight: 700;
          padding: 15px 40px;
          background-color: $primary-color;
          color: white;
          position: absolute;
          bottom: 200px;
          z-index: 999;
        }
        
        

      }
    }
  }
 
</style>