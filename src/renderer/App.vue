<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'AndroidTools'
}
</script>

<style lang="stylus">
  body,
  html
    padding 0
    margin 0
    height 100%
    font-family "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif
    border-radius 8px
    overflow hidden
  #app
    user-select none
    overflow hidden
    height 100%
  .el-button-group
    width 100%
    .el-button
      width 50%
</style>
