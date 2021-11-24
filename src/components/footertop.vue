<template>
  <footer>
      <!-- parte top footer  -->
      <section id="top_footer">
          <div class="container" id="container_top_footer" >
              <ul id="lista_top_footer">
                  <li v-for="link, i in links" :key="i" :id="link.svg? 'img_svg' : '' ">
                      <a :href="link.url">
                        <img class="img_top_footer" :src="link.immagine" :alt="link.descrizione">
                        <div class="link_name">{{link.descrizione}}</div>
                      </a>
                      
                  </li>
              </ul>
          </div>
      </section>

        <!-- parte centrale footer  -->
      <section>

      </section>

      <!-- parte bassa footer  -->
      <section>

      </section>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data(){
      return{
          links : [
              {
                  immagine : "../assets/img/digital.png",
                  descrizione : "DIGITAL COMICS",
                  url : "#"
              },
              {
                  immagine : "../assets/img/merchandise.png",
                  descrizione : "DC MERCHANDISE",
                  url : "#"
              },
              {
                  immagine : "../assets/img/subscrition.png",
                  descrizione : "SUBSCRIPTION",
                  url : "#"
              },
              {
                  immagine : "../assets/img/shop.png",
                  descrizione : "COMIC SHOP LOCATOR",
                  url : "#"
              },
              {
                  immagine : "../assets/img/visa.svg",
                  descrizione : "DC POWER VISA",
                  url : "#",
                  svg : true
              },
          ]
      }
  }
}
</script>


<style scoped>
#top_footer{
    background-color: rgb(0, 102, 255);
    height: 140px;
}
#container_top_footer{
    height: 100%;
}
ul{
    height: 100%;
    display: flex;
    justify-content: space-around;
    width: 100%;
}
#lista_top_footer li{
    display: flex;
}    
#lista_top_footer li a {
    display: flex;
    align-items: center;
    color: white;
    text-decoration: none;
    font-weight: bold;
}
.img_top_footer{
    width: 20%;
}
.link_name{
    margin-left: 10px;
}
#img_svg{
    max-width: 250px;
}
#img_svg img {
    width: 30%;
}
</style>
