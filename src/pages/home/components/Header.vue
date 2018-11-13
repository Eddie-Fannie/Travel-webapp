<template>
<div class="header">
  <div class="header-left">返回</div>
  <div class="header-input">输入城市/景点/游玩主题</div>
  <div class="header-right">城市</div>
</div>
</template>

<script>
    export default {
        name: 'HomeHeader'
    }
</script>
<style lang="sass" scoped>
  .header
    display: flex
    background: #00bcd4
    color: #fff
    height: 43px
    line-height: 43px
    .header-left
      width: 32px
      float: left
    .header-input
      flex: 1
      height: 32px
      line-height: 32px
      margin-top: 6px
      margin-left: 1px
      background: #fff
      border-radius: 5px
      color: #ccc
    .header-right
      width: 62px
      float: right
      text-align: center
</style>
