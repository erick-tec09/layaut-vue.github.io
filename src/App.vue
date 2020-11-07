<template>


  <router-view/>
</template>

<script>



export default {
  
}
</script>


<style lang="scss">

*, *::before, *::after{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.header__title{
   color: white;
   font-family: 'Noto Sans JP', sans-serif;
}

.header__section{

  height: 300px;
  background-image: linear-gradient(45deg, #333366  0%, #4b4bbe  100%);
  //clip-path: ellipse(100% 55% at 48% 44%);
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
