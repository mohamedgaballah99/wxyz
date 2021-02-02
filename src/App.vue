<template>
  <div id="app">
    <Toolbar></Toolbar>
    <Navbar></Navbar>
    <router-view />
  </div>
</template>
<script>
import Toolbar from "./components/Toolbar.vue";
import Navbar from "./components/Navbar.vue";

export default {
  components:{
    Toolbar,
    Navbar,
  }
}
</script>
<style lang="scss">
#app {
  font-family: 'Roboto', sans-serif;

  // height: 5000px;
}

#nav {
  padding: 0px;
}
::-webkit-scrollbar{
    width: 10px;
}
::-webkit-scrollbar-track{
   background-color: rgb(47, 48, 107);
}
::-webkit-scrollbar-thumb{
   background-color: rgb(47, 128, 248);
    border-radius: 20px;
}
</style>
