<template>
  <div id="app">

    <!-- Header  -->
    <MsHeader/>

    <!-- Jumbotron  -->
    <Jumbotron/>
    <!-- Main  -->
    <main>
      <MsMain/>
    </main>

    <!-- footer  -->
    <MsFooter/>
    
  </div>
</template>

<script>
import MsHeader from './components/Header.vue';
import MsMain from './components/Main.vue';
import MsFooter from './components/Footer.vue';
import Jumbotron from './components/Jumbotron.vue';





export default {
  name: 'App',
  components: {
    MsHeader,
    Jumbotron,
    MsMain,
    MsFooter
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
}
</style>
