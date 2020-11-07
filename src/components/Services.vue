<template>


    <section class="Services">

            <h2 class="Services__title">Why chose <span  class="Services__bold">MEDIKA</span></h2>
            <div  class="Services__items">
                <div class="Services__item">
                    <img class="Services__img" src="../assets/008-prescripcion.svg" alt="">
                    <h3 class="Services__subtitle">For Clinics</h3>
                    <p class="Services__desc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis quod aspernatur vero temporibus dolorem </p>

                </div>
                <div class="Services__item">
                    <img class="Services__img" src="../assets/009-medicina.svg" alt="">
                    <h3 class="Services__subtitle">For Clinics</h3>
                    <p class="Services__desc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis quod aspernatur vero temporibus dolorem </p>

                </div>
                <div class="Services__item">
                    <img class="Services__img" src="../assets/001-doctor-en-medicina.svg" alt="">
                    <h3 class="Services__subtitle">For Clinics</h3>
                    <p class="Services__desc">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Debitis quod aspernatur vero temporibus dolorem </p>

                </div>

            </div>
           

        
    </section>
    

</template>

<script>
export default {

}
</script>






<style scoped lang="scss">

.Services{

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 20px 0px;

    &__title{

        color: #38386ebb;
         font-family: 'Noto Sans JP', sans-serif;
         margin: 20px 0px;
            

    }
    &__bold{

    font-family: 'Noto Sans JP', sans-serif;
    color:#23235c;
            
    }
     &__items{

 display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
     &__item{

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 300px;
       
    }
     &__img{

         width: 100px;

    }
    &__subtitle{
    font-family: 'Noto Sans JP', sans-serif;
    text-align: center;
    margin: 10px 0px;
    }
    &__desc{

    color: #33336660;
    font-family: 'Noto Sans JP', sans-serif;
     text-align: center;
            
    }

}


</style>