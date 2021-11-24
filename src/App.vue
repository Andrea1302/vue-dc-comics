<template>
  <div id="app">

    <!-- Header  -->
    <MsHeader/>

    <!-- Main  -->
    <main>
      <msMain/>
    </main>

    <!-- footer  -->
    <FooterTop/>
    <FooterMain/>
    <Footerbottom/>
    
  </div>
</template>

<script>
import MsHeader from './components/Header.vue';
import msMain from './components/Main.vue';
import FooterTop from './components/Footertop.vue';
import FooterMain from './components/Footermain.vue';
import Footerbottom from './components/Footerbottom.vue';



export default {
  name: 'App',
  components: {
    MsHeader,
    msMain,
    FooterTop,
    FooterMain,
    Footerbottom
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.container{
  width: 70%;
  margin : 0 auto;
}
main{
  background-color: black;
  margin-top:5px;
}
</style>
