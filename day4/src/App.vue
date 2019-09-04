<template>
  <div id="app">
        <span v-for="(item,index) in list" :key="index">{{item}}</span>
  </div>
</template>

<script>
  export default {
    data(){
      return{
        list:["北京","上海","天津","重庆","北京"]
      }
    }
  }
</script>

<style lang="scss" scoped>
  *{
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    outline: none;
    user-select: none;
    appearance: none;
    box-sizing: border-box;
  }
  html,body,#app{
    width: 100%;
    height: 100%;
  }
</style>
