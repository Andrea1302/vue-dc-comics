<template>
    <section id="footermain">
        <div class="container" id="container_footermain">
            <nav>
                <div>
                    <ul>
                        DC COMICS
                        <li>
                            <a href="">
                                Characters
                            </a>
                        </li>
                         <li>
                            <a href="">
                                Comics
                            </a>
                        </li>
                         <li>
                            <a href="">
                                Movies
                            </a>
                        </li>
                         <li>
                            <a href="">
                                Tv
                            </a>
                        </li>
                         <li>
                            <a href="">
                                Games
                            </a>
                        </li>
                         <li>
                            <a href="">
                                Videos
                            </a>
                        </li>
                         <li>
                            <a href="">
                                News
                            </a>
                        </li>
                    </ul>

                    <ul>
                        SHOP
                        <li>
                            <a href="">
                                Shop DC
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Shop DC Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div id="central_nav">
                    <ul>
                        DC
                        <li>
                            <a href="">
                                Terms Of Use
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Privacy policy ( new)
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Ad Choices
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Advertising
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Jobs
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Subscriptions
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Talent Workshops
                            </a>
                        </li>

                        <li>
                            <a href="">
                                CPSC Certificates
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Ratings
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Shop Help
                            </a>
                        </li>

                        <li>
                            <a href="">
                                Contact Us
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <ul>
                        SITES
                        <li>
                            <a href="">
                                DC
                            </a>
                        </li>
                        <li>
                            <a href="">
                                MAD Magazine
                            </a>
                        </li>

                        <li>
                            <a href="">
                                DC Kids
                            </a>
                        </li>
                        <li>
                            <a href="">
                                DC Universe
                            </a>
                        </li>

                        <li>
                            <a href="">
                                DC Power Visa
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