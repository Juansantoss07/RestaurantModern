<script>
export default {
  name: "NavMobile",
  methods:{
      closemenu(){
          document.getElementById('nav').style.display = 'none'
      }
  }
};
</script>

<template>
  <div id="nav" class="navbar">
    <a href="#">home</a>
    <a href="#">about</a>
    <a href="#">menu</a>
    <a href="#">awards</a>
    <a href="#">contact</a>

    <i @click="closemenu" class="bi bi-x-lg"></i>
  </div>
</template>

<style scoped>
    .navbar{
        background: orange;
        color: #fff;
        height: 100vh;
        width:80%;
        position: fixed;
        z-index: 1000;
        right: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-evenly;
        transition: .5s;
        display: none;
    }

    .navbar a{
        color: #fff;
        text-decoration: none;
        background: none;
        font-size: 2em;
    }

    .navbar i{
        position: absolute;
        top: 0;
        margin: 1rem;
        right: 0;
        background: #111;
        border-radius: 50px;
        font-size: 2em;
        padding: 1rem;
        cursor: pointer;
    }
</style>