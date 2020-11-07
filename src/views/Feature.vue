<template>

   <Header/>
   <section class="Team">

      <h1 class="Team__title">Nuestros  Feature </h1>

     </section>
  
 
</template>

<script>

import Header from '@/components/Header.vue'
export default {
 name: 'Feature',
  components: {
    Header,
  }
}
</script>

<style lang="scss">

.Team{

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  &__title{
   
    color: #333366;
    margin: 20px 0px;
    text-transform: uppercase;
     font-family: 'Noto Sans JP', sans-serif;
  }
}

</style>