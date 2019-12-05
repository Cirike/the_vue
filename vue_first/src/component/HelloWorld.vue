<template>
    <div class="msg">
      <p>{{msg}}</p>
    </div>
</template>

<script>
    export default {
        data(){
          return {
            msg: "hi"
          }
        }


    }
</script>

<style scoped>
  .msg{
    color: red;
    heigh: 100 px;
    withd: 100 px
  }
</style>
