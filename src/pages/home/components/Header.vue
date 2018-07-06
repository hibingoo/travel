<template>
<div class="header">
    <div class="header-left">
        <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
        <span class="iconfont">&#xe632;</span>
        输入/城市/景点</div>
    <div class="header-right">城市
        <span class="iconfont arrow-icon">&#xe60c;</span>
    </div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~@/assets/styles/varsty.styl'
.header
  display flex
  line-height .86rem
  background $bgcolor
  color #ffffff
  .header-left
    width .64rem
    float left
    text-align center
    .back-icon
      font-size .4rem

  .header-input
    flex 1
    height .64rem
    margin-top .12rem
    margin-left .2rem
    padding-left .2rem
    border-radius .1rem
    background #ffffff
    color #cccccc
    line-height .64rem
  .header-right
    width 1.24rem
    float right
    text-align center
    .arrow-icon
      font-size .24rem

</style>
