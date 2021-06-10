<template>

  <ul class="view">
    <li v-for="(item,i) in product" v-bind:key="i"> 
      {{product[i].title}} 
    </li>
  </ul>

  <test> </test>

</template>

<script>
import vdata from './data.js'
import banner from './components/banner.vue'

export default {
  name: 'App',
  data(){
    return{
      product:vdata,
    }
  },
  components:{
    test:banner
  }
}
</script>

<style>
  *{padding: 0;margin: 0;}
  li{list-style: none;}
</style>
