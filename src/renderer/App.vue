<template>
  <div id="app" class="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
    name: 'wallpaper-mac',
    methods: {
      
    }
}
</script>

<style lang='less'>
  /* CSS */
  *{
    margin: 0px;
    font-family: 'PingFang SC',"Microsoft YaHei";
    box-sizing: border-box;
  }
  html,body,.app{
    width: 100%;
    height: 100%;
    background-color: transparent;
  }

  .el-loading-mask{
    background-color: rgba(255, 255, 255, 0.5) !important;
    font-size: 20px;
    color: #fff;
    .el-loading-spinner i {
      color: #fff;
      font-size: 50px;
    }
  }
</style>
