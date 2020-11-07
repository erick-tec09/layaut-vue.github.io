<template>
  
    
    <Header/>
     <section class="Team">

      <h1 class="Team__title">Nuestros  Aboud </h1>

     </section>
    
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
export default {
  name: 'Aboud',
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