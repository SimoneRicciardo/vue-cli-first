<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <div class="container-hero">

      <MyJumbo/>
  
      <MyTitle/>
   
   </div>


  </div>
</template>

<script>

import MyTitle from './components/MyTitle.vue'

export default {
  name: 'App',
  components: {
    MyTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container-hero{
  display: flex;
  align-items: center;
  justify-content: center;
  background-image: url("/img/Banque images_featured.webp");
  height: 50vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}
</style>
