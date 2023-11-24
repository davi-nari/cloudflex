<template>
    <NavBar/>
    <MainPage/>
    <FooterMain/>
</template>

<script>
import NavBar from './components/NavBar.vue';
import MainPage from './components/main/MainPage.vue';
import FooterMain from './components/main/footer/FooterMain.vue';
  export default {
  components: { NavBar, MainPage, FooterMain },
    
  }
</script>

<style>

</style>