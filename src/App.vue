
<template>

  <div>
    <link rel="stylesheet" href="https://use.typekit.net/uoa1cmf.css">
  <div id="app">
   
    <div id="nav">
         <img class="logo" src="./assets/Titre.png" width="185px" height="49px" >  
        <ul>
          <li><router-link to="/">Home</router-link> </li>   
          <li> <router-link to="/programmation">Programmation</router-link></li>
          <li> <router-link to="/actualite">Actualités</router-link></li>
          <li> <router-link to="/about">A propos</router-link></li>
          <li> <router-link to="/billeterie" class="bil" >billeterie</router-link> </li>
         
        </ul>
    </div>
    <router-view/>
  </div>
     


 
  </div>

  
</template>




<style lang="scss">







*{margin:0%;
padding: 0;}


#app {
 
  background-color: #FAE2D2;
  text-align: center;
  
}



#nav {
   width: 100%;
   height: 90px;
    font-family: quasimoda;
    font-weight:bold ;
    font-size: 20px;
    border: 1px  solid lightgrey;
   position: fixed;
    background-color: #FAE2D2;
 
  .logo{
    position: absolute;
    top: 20%; left: 4.5%;
  }

  .bil{
  color: #fce9d8;
  background-image: url("./assets/billeterie.png");
  background-size:100%;
  background-repeat: no-repeat;
  background-position: center;
  
  
  }

 

  ul {
    
    list-style-type: none;
     position: absolute;
    top:40%; left:40%;
    
    }

  li {
    display: inline; 
  }

  li a {   
    display: inline;
    color:#313131;   
    opacity: 0.7;
    padding: 24px;
    text-decoration: none;
  }
  
}
</style>
