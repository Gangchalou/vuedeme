<template>
  <div>
    <h2>vue第一份项目</h2>
    <img class="logo" src="./assets/logo.png" alt="logo">
    <HelloWorld/>

  </div>
</template>
<script>
  import HelloWorld from './components/HelloWorld.vue'
  export default {
    components:{
      HelloWorld
    }
  }
</script>
<style>
  .logo{
    width: 200px;
    height: 200px;
  }
</style>
