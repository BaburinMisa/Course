<script >
import SliderBlock from "@/assets/Components/SliderBlock.vue";
import TheFooter from "@/assets/Components/TheFooter.vue";
import TheHeader from "@/assets/Components/TheHeader.vue";
import MainFirst from "@/assets/Components/MainFirst.vue";
import MainSecond from "@/assets/Components/MainSecond.vue";
import SliderBlockTwo from "@/assets/Components/SliderBlockTwo.vue";
import MainThird from "@/assets/Components/MainThird.vue";
export  default {
  components: {TheFooter, SliderBlock, TheHeader, MainFirst, MainSecond, SliderBlockTwo,MainThird},
  data(){
    return{

    }
  }
}

</script>

<template>

  <li> <router-link to="/main">Главная</router-link>  </li>
  <li> <router-link to="/coffies">Кофейни</router-link> </li>
  <li> <router-link to="/about">О Нас</router-link> </li>
  <router-view />

</template>

<style>
  *{
    padding: 0;
    margin: 0;
  }
</style>
