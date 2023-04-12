<template>
  <navbar
  :logo="logo_src"
  :alt="app_name"
  />
  <router-view />
  <footerbar/>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footerbar from '@/components/Footerbar.vue'

export default {
  components:{
    Navbar,
    Footerbar
  },
  data(){
    return{
      logo_src: "/img/logo.png",
      app_name: "Make Your Burger"
    }
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;900&display=swap');

*{
  font-family: 'Roboto', sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-container{
  margin: 50px;
  min-height: 250px;
}

h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}

</style>
