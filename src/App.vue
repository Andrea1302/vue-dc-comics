<template>
  <div id="app">

    <!-- Header  -->
    <Header/>

    <!-- Main  -->
    <main>
    <Main/>

    </main>

    <!-- footer  -->
    <FooterTop/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/main.vue';
import FooterTop from './components/footertop.vue';


export default {
  name: 'App',
  components: {
    Header,
    Main,
    FooterTop
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
  width: 80%;
  margin : 0 auto;
}
main{
  background-color: black;
  margin-top:5px;
}
</style>
