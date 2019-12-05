<template>
  <div >
    <div class="logo">
      <img src="./assets/logo.png" alt="logo">
    </div>
    <div>
      <HelloWorld/>
    </div>
  </div>

</template>

<script>
    import HelloWorld from './component/HelloWorld';

    export default {
        components:{
          HelloWorld
        }
    }
</script>

<style scoped>
  .logo{
    position: center;
    height: 50px;
    width: 50px;
  }
</style>
