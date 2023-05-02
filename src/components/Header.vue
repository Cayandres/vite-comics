<script>
import { headerMenu } from '../data/menus';
export default {
  name:'Header',
  data(){
    return{
      headerMenu
    }
  }
  
}
</script>

<template>
  <header class="container">
    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
      <nav>
        <ul>
          <li v-for="(link, index) in headerMenu"
          :key="index"
          :class="{'active' : link.active}">{{link.label}}
            <a href="#"></a>
          </li>
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
        text-transform: uppercase;
        padding: 40px 5px;
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