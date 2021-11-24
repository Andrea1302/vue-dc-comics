<template>
  <div id="app">

    <!-- Header  -->
    <Header/>

    <!-- Main  -->
    <Main/>

    <!-- footer  -->
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/main.vue';
import Footer from './components/footer.vue';


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
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
</style>
