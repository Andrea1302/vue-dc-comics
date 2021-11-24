<template>
    <section id="footermain">
        <div class="container" id="container_footermain">
            <nav>
                <div>
                    <ul>
                        DC COMICS
                        <li v-for="link,i in linksDcComics" :key="i">
                            <a :href="link.url">
                                {{link.descrizione}}
                            </a>
                        </li>
                    </ul>

                    <ul>
                        SHOP
                        <li v-for="link,i in linksShop " :key="i">
                            <a :href="link.url">
                                {{link.descrizione}}
                            </a>
                        </li>
                        
                    </ul>
                </div>

                <div id="central_nav">
                    <ul>
                        DC
                        <li v-for="link,i in linksDC" :key="i">
                            <a :href="link.url">
                                {{link.descrizione}}
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <ul>
                        SITES
                        <li v-for="link,i in Sites" :key="i">
                            <a :href="link.url">
                                {{link.descrizione}}
                            </a>
                        </li>
                    </ul>
                </div>
            </nav>
            <div id="logo">
                <img src="../../public/assets/img/dc-logo-bg.png" alt="logo dc">
            </div>
        </div>
    </section>
    
  
</template>

<script>
export default {
  name: 'Footermain',
  data(){
      return{
          linksDcComics : [
              {
                  descrizione: "Characters",
                  url : "#"
              },
              {
                  descrizione: "Comics",
                  url : "#"
              },
              {
                  descrizione: "Movies",
                  url : "#"
              },
              {
                  descrizione: "Tv",
                  url : "#"
              },
              {
                  descrizione: "Games",
                  url : "#"
              },
              {
                  descrizione: "Video",
                  url : "#"
              },
              {
                  descrizione: "News",
                  url : "#"
              },
          ],
          linksShop : [
              {
                descrizione: "Shop DC",
                  url : "#" 
              },
              {
                descrizione: "Shop DC Collectibles",
                  url : "#" 
              }
          ],
          linksDC : [
              {
                  descrizione : "Terms Of Use",
                  url : "#"
              },
              {
                  descrizione : "Privacy policy ( new)",
                  url : "#"
              },
              {
                  descrizione : "Ad Choices",
                  url : "#"
              },
              {
                  descrizione : "Advertising",
                  url : "#"
              },
              {
                  descrizione : "Jobs",
                  url : "#"
              },
              {
                  descrizione : "Subscriptions",
                  url : "#"
              },
              {
                  descrizione : "Talent Workshops",
                  url : "#"
              },
              {
                  descrizione : "CPSC Certificates",
                  url : "#"
              },
              {
                  descrizione : "Ratings",
                  url : "#"
              },
              {
                  descrizione : "Shop Help",
                  url : "#"
              },
              {
                  descrizione : "Contact Us",
                  url : "#"
              }
            
          ],
          Sites : [
              {
                  descrizione : "DC",
                  url : "#"
              },
              {
                  descrizione : "MAD Magazine",
                  url : "#"
              },
              {
                  descrizione : "DC Kids",
                  url : "#"
              },
              {
                  descrizione : "DC Universe",
                  url : "#"
              },
              {
                  descrizione : "DC Power Visa",
                  url : "#"
              },
          ]
      }
  }
}
</script>


<style scoped>
    #footermain{
        background-image: url("../../public/assets/img/footer-bg.jpg");
        width: 100%;
        height: 300px;
        overflow: hidden;
    }
    #container_footermain{
        height: 100%;
        display: flex;
        justify-content: space-between;
        padding-top:40px ;
    }
    #logo img{
        width: 70%;
        position: relative;
        bottom: 70px;

    }
    nav{
        display: flex;
        color: white;
        font-weight: bold;
    }
    nav ul{
        margin-bottom: 20px;
    }
    nav li{
        list-style: none;
        margin: 2px 0;
        display: flex;
        align-items: center;
    }
    nav li a{
        text-decoration: none;
        font-size: .6rem;
        color:grey;
        display: inline-block;
        height: 100%;
    }
    #central_nav{
        margin: 0 30px;
    }
</style>