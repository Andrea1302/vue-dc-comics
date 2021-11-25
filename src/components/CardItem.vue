<template>
    <div id="card" >
        <img :src="details.thumb" :alt="details.series">
        <div id="description">
            {{details.series}}
        </div>
    </div>
</template>

<script>
export default {
  name: 'CardItem',
  props : {
    details : Object
  }
}
</script>


<style scoped >
    #section_cards{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
    }
    #card{
        width: calc(( 100% / 6 ) - 10px );
        margin: 10px 5px;
        cursor: pointer;
    }
    #card img{
        width: 100%;
        aspect-ratio: 1;
        object-fit: cover;
        object-position: top;
    }
    #card #description{
        font-size: .6rem;
        font-weight: bold;
    }
    
</style>