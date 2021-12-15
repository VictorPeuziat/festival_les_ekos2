
<template>

  <div>
    <link rel="stylesheet" href="https://use.typekit.net/uoa1cmf.css">
  <div id="app">
   
    <div id="nav">
         <img class="logo" src="./assets/Titre.png" width="7%" height="50%" >  
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
   height: 50px;
    font-family: quasimoda, sans-serif;
    font-weight:bold ;
    font-size: 12px;
    border: 1px  solid lightgrey;
   position: fixed;
    background-color: #FAE2D2;
 
  .logo{
    position: absolute;
    top: 20%; left: 4.5%;
  }

  .bil{
  color: white;
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
    color:#876956;   
    padding: 24px;
    text-decoration: none;
  }
  
}
</style>
