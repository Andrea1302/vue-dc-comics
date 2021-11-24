<template>
    <section id="footerbottom">
        <div class="container" id="contenitore_footer_bottom">
            <div>   
                 <button>
                    Sign-UP NOW!
                </button>
            </div>
           

            <nav>
                <div>
                    FOLLOW US
                </div>
                <ul>
                    
                    <li>
                        <a href="#">
                            <img src="../../public/assets/img/footer-facebook.png" alt="facebook logo">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../public/assets/img/footer-twitter.png" alt="facebook logo">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../public/assets/img/footer-youtube.png" alt="facebook logo">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../public/assets/img/footer-pinterest.png" alt="facebook logo">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../public/assets/img/footer-periscope.png" alt="facebook logo">
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </section>
    
  
</template>

<script>
export default {
  name: 'Footerbottom',
}
</script>


<style scoped>
    #footerbottom{
        background-color: rgb(37, 37, 37);
    }
    #contenitore_footer_bottom{
        display: flex;
        height: 100px;
        align-items: center;
        justify-content: space-between;
    }
    button{
        padding: 8px;
        border: 2px solid rgb(0, 102, 255);
        background-color: rgba(0, 0, 0, 0);
        color: white;
        font-weight: bold;
    }
    nav{
        display: flex;
        align-items: center;
        color: rgb(0, 102, 255);
        font-weight: bold;
    }
    nav ul {
        display: flex;
        
    }
    ul li{
        margin: 0 20px;
        list-style: none;
    }
    li a {
        text-decoration: none;
    }
</style>