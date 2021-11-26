<template>
  <div id="app">
    <Header/>
    <Nav/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Nav from './components/Nav.vue'

export default {
  name: 'App',
  components: {
    Header,
    Nav
    
  }
}
</script>

<style>
@import './styles/reset.css';

#app{
  height:auto;
  width: 100%;
  height: 100vh;
  display: grid;
  grid-template-columns: repeat(6,1fr);
  grid-template-rows:20% 15% 30%;
  grid-template-areas: ". . header header . ."
                       ". nav nav nav nav ."
                       "boxPic boxPic boxPic boxPic boxPic boxPic";
  justify-items: start;
  }

header {
  width: 100%;
  height:90%;
  grid-area: header;
}
nav{
  width: 100%;
  height: 60%;
  grid-area: nav;  
}


</style>