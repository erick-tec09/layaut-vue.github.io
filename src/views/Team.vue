<template>
  
    
    <Header/>
  
  <section class="Team">

      <h1 class="Team__title">Nuestros  Equipo </h1>

      <ul>
        <li > </li>
      </ul>

  </section>


 
    
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
export default {
  name: 'Team',
  components: {
    Header,
  },
  data() {
    return {
      usuarios: [],
        
      
    }
  },
  methods: {
     async getInfoUsers(){

            const info = await fetch('https://jsonplaceholder.typicode.com/users')
            const data = await info.json();
            this.usuarios = data

        }



    },
    created() {
        
        this.getInfoUsers();
    
  },
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