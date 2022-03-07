<script>
  import Header from "./components/Header.vue";
  import Home from "./components/sections/Home.vue";
  import NavMobile from "./components/NavMobile.vue"
  export default{
    name: "app",
    components:{ 
      Header,
      Home,
      NavMobile
    }
  }
</script>

<template>
    <NavMobile/>
    <Header/>
    <Home/>
</template>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background-color: #111;
  }

  .content{
    width:100%;
  }
</style>