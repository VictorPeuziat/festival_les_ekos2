<template>
<div>
<h1> Voici les actualités </h1>
<Insta />
<Footer />
</div>

</template>


<script>

import Footer from '../components/footer.vue'
import Insta from '../components/instagram.vue'

export default {
  
  components:{
    Footer,
    Insta
  }
}
</script>