<template>
    <section id="footermain">
        <div class="container" id="container_footermain">
            <nav>
                <div>
                    <ul>
                        DC COMICS
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                         <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                    </ul>

                    <ul>
                        SHOP
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                    </ul>
                </div>

                <div id="central_nav">
                    <ul>
                        DC
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <ul>
                        SITES
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>
                        <li>
                            <a href="">
                                prova
                            </a>
                        </li>

                        <li>
                            <a href="">
                                prova
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
        height: 15px;
    }
    nav li a{
        text-decoration: none;
        font-size: .6rem;
        color:grey;
    }
    #central_nav{
        margin: 0 30px;
    }
</style>