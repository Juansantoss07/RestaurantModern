<script>
export default {
    name:"Header",
    methods:{
        openmenu(){
            document.getElementById('nav').style.display = 'flex';
        }
    }
}
</script>

<template>
    <div class="content">
        <header>
            <div class="logo">
                <strong>RestaurantModern</strong>
            </div>
            <div class="links-header">
                <a href="#">home</a>
                <a href="#">about</a>
                <a href="#">menu</a>
                <a href="#">awards</a>
                <a href="#">contact</a>
            </div>
            <div class="book">
                <a href="#">Login</a> /
                <a href="#">Registration</a> |
                <a href="#">Book Table</a>
            </div>
            <div class="btn-mobile">
                <i @click="openmenu" class="bi bi-three-dots"></i>
            </div>
        </header>
    </div>
</template>

<style scoped>
    header{
        display: flex;
        width: 100%;
        padding: 1rem 2rem;
        justify-content: space-between;
        align-items: center;
        color: #fff;
    }

    .links-header{
        display: flex;
        width: 350px;
        justify-content: space-around;
        align-items: center;
    }

    .book{
        display: flex;
        width: 250px;
        justify-content: space-around;
        align-items: center;
    }

    a{
        color: #fff;
        text-decoration: none;
        text-transform: capitalize;
        font-weight: 500;
    }

    a:hover{
        color: #ffa500;
    }

    strong{
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        text-transform: uppercase;
    }

    .btn-mobile{
        display: none;
    }
    .btn-mobile i:hover{
        color: #ffa500;
    }

    @media(max-width:930px){
        .links-header, .book{
            display: none;
        }

        .btn-mobile{
            display: flex;
        }
    }
</style>