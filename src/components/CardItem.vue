<template>
    <div id="container_section_cards">
        <span id="current_series">
            CURRENT SERIES
        </span>
        <div id="section_cards">
            <div id="card" >
                <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
                <div id="description">
                    ACTION COMICS
                </div>
            </div>
            
        </div>

        <div id="load">
            <span id="info">LOAD MORE</span> 
        </div>
        
    </div>
   
</template>

<script>
export default {
  name: 'CardItem',
}
</script>


<style scoped >
    #container_section_cards{
        width: 100%;
    }
    
    #current_series{
         background-color: rgb(0, 102, 255);
        padding: 5px 10px;
        font-weight: bold;
        position: relative;
        bottom: 30px;
    }
    #section_cards{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
    }
    #card{
        width: calc(( 100% / 6 ) - 10px );
        margin: 10px 5px;
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
    #load{
        text-align: center;
        margin-bottom: 10px;
    }
    #info{
        background-color: rgb(0, 102, 255);
        padding: 5px 30px;
        font-weight: bold;
        font-size: .6rem;
        cursor: pointer;
    }
</style>