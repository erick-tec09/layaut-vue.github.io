<template>



    <section class="carrusel">

        <div class="carrusel__desc">
            <p class="carrusel__parrafo"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed, asperiores? Ex, nobis. Fuga fugit harum voluptas. .</p>

        </div>
        <div class="carrusel__items">
             <img src="../assets/spotifi.png" alt="">
            <img src="../assets/spotifi.png" alt="">
            <img src="../assets/spotifi.png" alt="">
            <img src="../assets/spotifi.png" alt="">
        </div>
       
    </section>  

</template>

<script>
export default {

}
</script>






<style scoped lang="scss">
.carrusel{

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 300px;


    &__parrafo{

        margin: 20px 0px;
        color: #33336660;
         font-family: 'Noto Sans JP', sans-serif;
            
    }
    &__items{
        display: flex;
        flex-direction: row;
        img{
            width: 100px;
            margin: 0px 20px;
        }
    }
            
}
</style>