<template>

 <section class="hero">

     <img  class="hero__img" src="../assets/banner.png" alt="">
     
     <h2 class="hero__title">Conecting Patiens & medical Organizatios</h2>
     <p class="hero__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, voluptas quidem temporibus exercitationem adipisci assumenda cumque fa</p>
     <a href="" class="hero__btn">FREE TRIAL</a>

 </section>


</template>

<script>
export default {

name: 'Hero',
}
</script>

<style  scoped lang="scss">
.hero{
    
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
    top: 50%;
    left: 50%; transform: translate(-50%, -50%);
   
    &__img{
        widows: 200px;
        height: 300px;
    }

    &__title{

        color: #333366;
         font-family: 'Noto Sans JP', sans-serif;
         font-weight: 600;
         font-size: 30px;
         width: 350px;
         margin-top: 10px;
         text-align: center;
        
        
    }
     &__desc{
           font-family: 'Noto Sans JP', sans-serif;
            color: #33336660;
             width: 450px;
             text-align: center;
             margin: 10px 0px;
    }
    &__btn{

        text-transform: uppercase;
        text-decoration: none;
        background: rgb(255, 179, 0)  ;
        color: white;
         padding: 10px 20px;
         border-radius: 20px;
         transition: all 0.3s;
         font-family: 'Noto Sans JP', sans-serif;
         font-weight: lighter;
         font-size: 14px;
         &:hover{
              background: rgb(251, 200, 30)  ;
         }

    }
}
</style>