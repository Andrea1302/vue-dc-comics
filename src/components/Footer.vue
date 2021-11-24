<template>
    <footer>
        <FooterTop/>
        <FooterMain/>
        <Footerbottom/>
    </footer>
 
</template>


<script>

import FooterTop from './Footertop.vue';
import FooterMain from './Footermain.vue';
import Footerbottom from './Footerbottom.vue';

export default {
  name: 'MsFooter',
  components: {
    FooterTop,
    FooterMain,
    Footerbottom
  }
}

</script>


<style scoped >
  
   
</style>
