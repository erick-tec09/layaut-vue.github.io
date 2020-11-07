
<template>
<section  class="header__section">


   <header class="header">
        <div class="header__logo">

          <img  class="hedaer__img" src="../assets/007-embarazada.svg" alt="">
           <h1  class="header__title">  Medika</h1>
        </div>
        <nav>
            <ul class="header__menu">
                <router-link class="header__link" to="/">Home</router-link> 
                <router-link class="header__link" to="/about">About US</router-link>
                <router-link class="header__link" to="/feature">Feature</router-link>
                <router-link class="header__link" to="/Parnerts">Our Parnets</router-link>
                <router-link class="header__link" to="/precie">Precie</router-link>
                <router-link class="header__link" to="/team">Teams</router-link>
            </ul>
        </nav>
 </header>
 </section>

</template>

<script>
export default {

 name: 'Header',
}
</script>

<style scoped lang="scss">


*, *::before, *::after{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.header__logo {
    display: flex;
    justify-content: center;
    align-content: center;
}

.hedaer__img {
   
    height: 30px;
}
  

.header__title{
   color: white;
   font-family: 'Noto Sans JP', sans-serif;
}

.header__section{

  height: 380px;
  background-image: linear-gradient(45deg, #333366  0%, #4b4bbe  100%);
  //clip-path: ellipse(100% 55% at 48% 44%);
  position: relative;
}

.header{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
     align-items: center;
    height: 80px;

    margin-bottom: 20px;

    &__list{

        list-style: none;
    }
     &__link{

         text-decoration: none;
         color:white;
         margin: 0px 20px;
         font-family: 'Noto Sans JP', sans-serif;
         &:hover{
           color: #ffffff;
           
           
         }
        
    }
}


</style>