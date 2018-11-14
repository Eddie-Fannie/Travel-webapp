<template>
<div class="header">
  <div class="header-left">
    <div class="iconfont back-icon">&#xe624;</div>
  </div>
  <div class="header-input">
    <span class="iconfont">&#xe632;</span>
    输入城市/景点/游玩主题</div>
  <div class="header-right">城市
  <span class="iconfont arrow-icon">&#xe64a;</span>
  </div>
</div>
</template>

<script>
    export default {
        name: 'HomeHeader'
    }
</script>
<style lang="sass" scoped>
  @import '~styles/varibles.scss'
  .header
    display: flex
    background: $bgColor
    color: #fff
    height: 43px
    line-height: $headerHeight
    .header-left
      width: 32px
      float: left
      .back-icon
        text-align: center
        font-size: 2px
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
      min-width: 52px
      padding: 0 .1rem
      float: right
      text-align: center
      color: #fff
      .arrow-icon
        margin-left: -2px
        font-size: 12px
</style>
