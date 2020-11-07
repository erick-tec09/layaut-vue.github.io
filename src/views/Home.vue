<template>
  
    <Header/>
    <Hero/>
    <Carrusel/>
    <Services/>
 
</template>

<script>

// @ is an alias to /src
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Carrusel from '@/components/Carrusel.vue'
import Services from '@/components/Services.vue'

export default {
  name: 'Home',
  components: {
    Header, Hero,Carrusel,Services
  }
}
</script>
