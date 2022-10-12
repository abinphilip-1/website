<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <MainHero></MainHero>
    <DisplayComponent></DisplayComponent>
    <StackComponent></StackComponent>
    <FooterComponent></FooterComponent>

  </div>
</template>

<script>
// @ is an alias to /src

import MainHero from '@/components/MainHero.vue';
import DisplayComponent from '../components/DisplayComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
import StackComponent from '@/components/StackComponent.vue';

export default {
  name: 'HomeView',
  components: {
    MainHero,
    DisplayComponent,
    FooterComponent,
    StackComponent
}
}
</script>
<style>
    body{
        /* transition: 0.7s; */
        margin: 0;
        padding: 0;
        background-color: rgb(255, 255, 255);
        font-family: 'Poppins', sans-serif;
        color:rgb(57,57,57);
    }

    

</style>