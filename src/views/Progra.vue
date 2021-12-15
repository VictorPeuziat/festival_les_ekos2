<template>
    <div class="programmation">
        <h1>Programmation</h1>
        <br>
        <Progra_gauche />
        <br>
        <Footer />
    </div>
</template>


<script>

import Footer from '../components/footer.vue'
import Progra_gauche from '../components/progra_gauche.vue'

export default {
  
  components:{
    Footer,
    Progra_gauche
  }
}
</script>