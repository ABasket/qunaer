<template>
  <div id="homeheader">
    <div class="header">
      <div class="header-left back-icon">
        <div class="iconfont">&#xe624;</div>
      </div>
      <div class="header-input">
        <span class="iconfont">&#xe632;</span>
        输入城市/景点/游玩主题</div>
      <div class="header-right arrow-icon">
        <span class="city">城市</span>
        <span class="iconfont">&#xe64a;</span>
      </div>
    </div>
  </div>

</template>
<script>
export default {
  name: 'homeheader'
}
</script>
<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display flex
    line-height: .86rem
    background $bgColor
    color: #fff
    .header-left
        width: .64rem
        float left
      .back-icon
        text-align center
        font-size .4rem
    .header-right
      font-size 0
      width: 1.24rem
      float right
      text-align center
      .arrow-icon
        font-size .24rem
      .city
        font-size .3rem
    .header-input
      flex:1
      background #fff
      border-radius .1rem
      margin-top: .12rem
      margin-left: .2rem
      padding-left .2rem
      height .64rem
      line-height .64rem
      color: #ccc

</style>
