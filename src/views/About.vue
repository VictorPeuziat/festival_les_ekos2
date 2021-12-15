


<template>
  
  <div class="about">
 
    <h1>Qu'est ce que le festival les ekos ? </h1>
           <div class="textBox">
            <p> Une association à but non-lucratif souhaitant recréer du lien entre les personnes après la crise sanitaire pour partager un moment convivial ! 🤝<br>
             C’est l’envie de développer le projet fou d’un festival écologique, ayant pour but de sensibiliser les participants à l'impact humain sur notre planète 🌍<br>
             Nous avons besoin de votre soutien pour concrétiser notre projet !<br>
             Les bénéfices seront reversés à une association luttant pour NOTRE planète !<br>
             N'hésitez pas à partager notre projet autour de vous 😉<br><br></p>
               
      </div> 
    <h1>Qui somme nous ?</h1>
    <br>
    <div class="photo">
      <img class="img_ronde" src="../assets/Bob-leponge.png" width="10%" >
      <img class="img_ronde" src="../assets/Bob-leponge.png" width="10%" >
      
    </div>
   <Footer />
  </div>
</template>

<style lang="scss">
.img_ronde {
border-radius: 50%;
}

h1, p{
  font-family: hobeaux, sans-serif;
    font-style: normal;
}
</style>

<script>

import Footer from '../components/footer.vue'


export default {
  
  components:{
    Footer
    
  }
}
</script>
