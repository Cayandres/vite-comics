<script>
export default {
  name:'Header'
  
}
</script>

<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
      <nav>
        <ul>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">1</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>


<style lang="scss" scoped>
  @use "../scss/general/variables" as*;
  @use "../scss/general/mixin" as*;

  header{
    @include beetweenAround("beetween");
    align-items: center;
    ul{
      display: flex;
      li{
        margin: 20px;
        padding: 20px;
        a{
          color: black;
            &:hover{
              color: $primary-color;
            }
        }
      }
    }
  }
 




</style>