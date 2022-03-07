<script>
export default {
    name:"ImgHome"
}
</script>

<template>
    <div class="content">
        <div class="image">
            <img src="https://images.pexels.com/photos/6485578/pexels-photo-6485578.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="">
        </div>
    </div>
</template>

<style scoped>
    .image{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .image img{
        width: 80%;
    }

    @media(max-width:680px){
        .image img{
            width: 50%;
        }
    }
</style>