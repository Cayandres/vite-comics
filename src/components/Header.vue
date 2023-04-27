<script>
export default {
  name:'header'
  
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
        list-style: none;
        margin: 20px;
        padding: 20px;
        a{
          text-decoration: none;
          color: black;
            &:hover{
              color: $primary-color;
            }
        }
      }
    }
  }
 




</style>