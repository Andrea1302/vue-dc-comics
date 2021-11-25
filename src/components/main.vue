<template>
    <div class="container">
        <section>
            <CardItem/>
        </section>
    </div>
  
</template>


<script>
import CardItem from './CardItem.vue';

export default {
  name: 'msMain',
  components: {
    CardItem,
  }
}
</script>


<style scoped>
    section{
        color: white;
        width: 100%;
    }
</style>
