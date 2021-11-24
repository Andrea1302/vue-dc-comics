<template>
<div class="container">
   <header>
    <!-- logo  -->
    <img src="../../public/assets/img/dc-logo.png" alt="logo dc comics">

    <nav>
      <ul>
        <li v-for="link,i in links" :key="i">
          <a :href="link.url" :class="link.active ? 'active' : '' ">{{link.text}}</a>
        </li>
      </ul>
    </nav>
  </header>
</div>
 
</template>

<script>
export default {
  name: 'MsHeader',
  data(){
  return{
    links : [
      {
        text : "CHARACTER",
        url : "#",
        active : false
      },
      {
        text : "COMICS",
        url : "#",
        active : true
      },
      {
        text : "MOVIES",
        url : "#",
        active : false
      },
      {
        text : "TV",
        url : "#",
        active : false
      },
      {
        text : "GAMES",
        url : "#",
        active : false
      },
      {
        text : "COLLECTIBLES",
        url : "#",
        active : false
      },
      {
        text : "VIDEOS",
        url : "#",
        active : false
      },
      {
        text : "FANS",
        url : "#",
        active : false
      },
      {
        text : "NEWS",
        url : "#",
        active : false
      },
      {
        text : "SHOP",
        url : "#",
        active : false,
      }

    ]
  }
}
}

</script>


<style scoped >
  header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    min-height: 100px;
  }
  nav {
    height: 100px;
  }
  nav ul {
    height: 100%;
  }
  header li {
    list-style: none;
    height: 100%;
    line-height: 100px;
    vertical-align: middle;
    display: inline-block;
    margin :0 20px;
  }
  header img{
    width: 80px;
    height: auto;
  }
  li a.active{
    color :rgb(0, 102, 255);
    border-bottom: 4px solid rgb(0, 102, 255) ;
  }
  li a{
    color: black;
    text-decoration: none;
    font-size: .6rem;
    display: inline-block;
    font-weight: bold;
  }
  /* @media all and ( max-width:780px){
    header li {
      display: none;
      
    }
  } */
</style>
