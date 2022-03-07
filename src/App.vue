<script>
  import Header from "./components/Header.vue";
  import Home from "./components/sections/Home.vue";
  import NavMobile from "./components/NavMobile.vue";
  import About from "./components/sections/About.vue"
  export default{
    name: "app",
    components:{ 
      Header,
      Home,
      NavMobile,
      About
    }
  }
</script>

<template>
    <NavMobile/>
    <Header/>
    <Home/>
    <About/>
</template>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  body{
    background: #111;
  }

  .content{
    width:100%;
  }

  .btn-home {
    border: none;
    background: transparent;
    border:2px solid  #ffa500;
    color: #fff;
    width: 180px;
    padding: .5rem 0rem;
    margin-top: 1rem;
    cursor: pointer;
    font-weight: 500;
}

.btn-home:hover{
    background: #ffa500;
    color: #fff;
}
</style>