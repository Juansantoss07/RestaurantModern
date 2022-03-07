<script>
export default {
    name:"About"
}
</script>

<template>
    <div class="content">
        <section class="section-about">
            <div class="about-box">
                <h1>About Us</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor quaerat, blanditiis explicabo id quae nostrum at eius dolorem neque accusantium quibusdam itaque doloribus ullam enim necessitatibus eligendi vel dicta excepturi.</p>
                <button class="btn-home">
                    Learn More
                </button>
            </div>
             <div class="about-box2">
                <h1>Our Histoty</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor quaerat, blanditiis explicabo id quae nostrum at eius dolorem neque accusantium quibusdam itaque doloribus ullam enim necessitatibus eligendi vel dicta excepturi.</p>
                <button class="btn-home">
                    Learn More
                </button>
            </div>
        </section>
    </div>
</template>

<style scoped>
    .section-about{
        display: flex;
        height: 100vh;
        width: 100%;
        background-image: url("https://cdn.pixabay.com/photo/2014/06/16/23/39/black-370118_960_720.png");
        background-position: center;
        background-size: cover;
        background-attachment: fixed;
        justify-content: space-between;
        align-items: center;
        padding: 0 2rem;
    }

    .about-box{
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        width: 45%;
        color: #fff;
    }

    .about-box2{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        width: 45%;
        color: #fff;
    }

    .about-box h1, .about-box2 h1{
        font-size: 3em;
        color: #ffa500;
        font-family: "Dancing Script", cursive;
    }

    .about-box p, .about-box2 p{
        margin: 1rem 0;
    }

    @media(max-width:680px){
        .section-about{
            flex-direction: column;
            justify-content: space-evenly;
        }

        .about-box, .about-box2{
            width:100%;
        }
    }
    
</style>