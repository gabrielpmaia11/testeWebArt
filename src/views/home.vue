<template>
    <v-app>
        <NavBar class ="index" />
        
    </v-app>
</template>


<script>
    import Navbar from "../components/PrimeiroComponenteVue";
  
    export default {
        name : 'Home',
        components:{
            Navbar,

        }
    }
</script>


<style scoped>
    .index{
        background-color: black;
    }
</style>