


<template>

  <div>
     <link rel="stylesheet" href="https://use.typekit.net/uoa1cmf.css">
  <br>
  <br>
  <div class="Ellipse-1"> 
    <span class="Festival">
      Festival
    </span>
    <span class="Les-kos">
    Les Ékos
    </span>
    <span class="text_home">
      Lorem ipsum dolor sit amet, consetetur, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo
    </span>
      <router-link to="/" class="decouvrir">Découvrir</router-link> 
<router-view/>
  </div>
  <span class="Lorem_ipsum">
    Lorem ipsum
  </span>
  <img class="illu" src="../assets/Illustration_Page_Accueil.png" >
  <br>
  <span class="actus">
    Nos Actualités
  </span>
  
  
  
  
<Footer />

  </div>
</template>

<script>
import Footer from '../components/footer.vue'

export default {
  
  components:{
    Footer
  }
}
</script>


<style lang="scss">

.Lorem_ipsum{
  width: 413px;
  height: 50px;
 margin-right: 50%;
 margin-top:500px;
  font-family: Hobeaux;
  font-size: 50px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: 1px;
  text-align: left;
  color: #6cbfaf;
}

.illu{
  width: 55%;
  height: 45%;
  margin-top:-100px;
  margin-left: 45%;
  }
  
.actus{

  

  font-family: Hobeaux;
  margin-left: -750px;
  margin-top: 500px;
  font-size: 35px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: 1.3px;
  text-align: left;
  color: #eb7659;
}

.Festival {
  width: 305px;
  height: 96px;
  margin: -300px 300px -20px 0;
  font-family: Quasimoda;
  font-size: 52px;
  font-weight: 900;
  letter-spacing: 1.6px;
  text-align: left;
  color: #313131;
}
.Les-kos {
  width: 603px;
  height: 191px;
  margin: 20px 0 70px;
  white-space: nowrap;
  font-family: Hobeaux;
  font-size: 110px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  letter-spacing: 3.2px;
  text-align: left;
  color: #eb7659;
  display: inline; 
}

.Ellipse-1 {
  width: 250px;
  height: 250px;
  margin: -120px 117px 29.7px -90px;
  padding: 289px 301px 236px 205px;
  border: solid 1px rgba(136, 136, 136, 0.5);
  background-color: #fce9d8;
  border-radius: 50%;
}

.text_home{
   width: 534px;
  height: 129px;
  margin: 45px 60px 104.6px 9px;
  opacity: 0.7;
  font-family: Quasimoda;
  font-size: 11px;
  font-weight: 350;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.30;
  letter-spacing: 0.23px;
  text-align: left;
  color: #313131;
}

  .decouvrir{
    background-image: url("../assets/shape_bleu.png");
    background-size:100%;
  background-repeat: no-repeat;
  background-position: center;
  text-decoration: none;
  width: 109px;
  height: 28px;
  font-family: Hobeaux;
  font-size: 19px;
  padding:6px;
  font-weight: 600;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  display: flex;
  margin-top: 10%;
  letter-spacing: 0.52px;
  
  color: #fce9d8;
  }

  .fest{
    font-family: quasimoda, sans-serif ;
    color: black;


  }

  .bas{
    height: 100%;
    width: 100%;
  }

</style>