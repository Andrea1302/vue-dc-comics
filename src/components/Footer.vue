<template>
    <footer>
        <FooterTop/>
        <FooterMain/>
        <Footerbottom/>
    </footer>
 
</template>


<script>

import FooterTop from './MsFooterTop.vue';
import FooterMain from './MSFooterMain.vue';
import Footerbottom from './MsFooterBottom.vue';

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
