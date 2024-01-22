<script>
import Header from './Header.vue';
import Places from './Places.vue';
import Footer from './Footer.vue';

 export default{

  components:{
    Header, Places, Footer
  }

 } 
</script>

<template>
  <Header></Header>
  <Places></Places>
  <Footer></Footer>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200;300;400;500;600;700&display=swap');
    *{
        font-family: Oswald;
    }
    .container{
        max-width: 1110px;
        margin-left: auto;
        margin-right: auto;
        height: 100%;
    }
</style>
