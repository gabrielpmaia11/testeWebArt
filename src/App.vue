<template>
  <PrimeiroComponenteVue/>

  <section-categorie-vue/>

  <FooterVue/>

</template>

<script>
import PrimeiroComponenteVue from "./components/PrimeiroComponente.vue";
import SectionCategorieVue from './components/SectionCategorie.vue';
import FooterVue from "./components/Footer.vue";
 

export default{
  name: 'App',
    components:{
      PrimeiroComponenteVue,
      SectionCategorieVue,
      FooterVue,
   

    }
     
} 


</script>
<style scoped>
  .index{
    background-color:#ff5001;
  }
</style>