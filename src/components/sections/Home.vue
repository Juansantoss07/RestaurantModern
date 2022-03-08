<script>
import TextHome from "../TextHome.vue"
import ImgHome from "../ImgHome.vue"
export default {
    name:"Home",
    components:{
    TextHome,
    ImgHome
}
}
</script>

<template>
    <div class="content">
        <section class="section-home">
            <TextHome/>
            <ImgHome/>
        </section>  
    </div>
</template>

<style scoped>
    .section-home{
        display: flex;
        height: 100vh;
        align-items: center;
        justify-content: space-between;
        padding: 2rem 0;
    }


    @media(max-width:680px){
        .section-home{
            flex-direction: column;
            justify-content: space-evenly;
            height: auto !important;
        }
    }
</style>