<template>
  <div class="container">
    <div class="common item1"><span>
      <router-link to="/loading">loading...</router-link></span></div>
    <div class="common item2"><span>弹出框</span></div>
    <div class="common item3"><span>分页组件</span></div>
    <div class="common item4"><span>加载列表</span></div>
    <div class="common item5"><span>ajax请求加载</span></div>
    <div class="common item6"></div>
    <div class="common item1"></div>
    <div class="common item2"></div>
    <div class="common item3"></div>
  </div>
</template>
<script>
  export default {
    name: 'index'
  }
</script>

<style scoped>
  .container {
    display: flex;
    /*flex-direction: column;
    flex-wrap: wrap;*/
    flex-flow: row wrap;
    justify-content: center;
  }

  .common {
    width: 100px;
    height: 100px;
    text-align: center;
    line-height: 100px;
    margin: 10px;
    color: #fff;
    font-weight: bold;
  }

  .item1 {
    background-color: blue;
  }
  .item2 {
    background-color: green;
  }
  .item3 {
    background-color: black;
  }
  .item4 {
    background-color: gray;
  }
  .item5 {
    background-color: #18c183;
  }
  .item6 {
    background-color: red;
  }
</style>
