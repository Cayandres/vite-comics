
<script>
export default {
  name: 'ProductCard',
  props:{
    image: String,
    productName: String
  }
}
</script>

<template>
    <div class="card">
      <div class="card-image">
        <img :src="image" :alt="productName">
      </div>
      <h4>{{ productName }}</h4>
    </div>  
</template>

<style lang="scss" scoped>
@use "../../scss/general/variables" as*;
        .card{
          height: 300px;
          width: calc(100%/6);
          .card-image{
            aspect-ratio: 1/1;
            height: 200px; 
            overflow: hidden;
            img{
              width: 90%;
              object-fit: cover; 
            }
          }
          h4{
            padding-top: 10px;
          }
        }
</style>