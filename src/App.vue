
<template>
  <div>
    
  <div id="app">
   
    <div id="nav">
     
    <ul><li>  <router-link to="/">Home</router-link> </li>
     
     <li> <router-link to="/programmation">Programmation</router-link></li>
     <li><img src="./assets/Titre.png" width="200px" height="80px"></li>
     <li> <router-link to="/actualite">Actualités</router-link></li>
     <li> <router-link to="/about">A propos</router-link></li>
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
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: url('~@/assets/Motifs.jpg');
}

#nav {
  padding: 5px;

ul {
    list-style-type: none;
    margin: 10;
    padding: 10;
    overflow: hidden;
    
}

li {
  display: inline;
   
}

li a {
    display: inline;
    color:#6EBFAF;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
    background-color: #876956;
}
  
}
</style>
