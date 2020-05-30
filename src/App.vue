<template>
  <div id="app">
    <Choose></Choose>
<!--    <Reg></Reg>-->
  </div>
</template>

<script>

  import Choose from "@/components/Choose";
  // import Reg from "@/components/Reg";

export default {
  name: 'App',
  components:{
    Choose,
    // Reg
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
