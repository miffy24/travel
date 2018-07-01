<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">城市<span class="iconfont arrow-icon">&#xe64a;</span></div>
  </div>
</template>
<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
 .header
  display: flex
  line-height: .86rem
  color: #fff
  background: $bgColor;
  .header-left
    width: .64rem
    float: left
    text-align: center
    .back-icon
      text-align: center
      font-style: .4rem;
  .header-input
    flex: 1
    height: .64rem
    line-height: .64rem
    margin-top: .12rem
    border-radius: .1rem
    padding-left: .2rem;
    margin-left: .2rem;
    margin-right: .2rem;
    background: #fff;
    color: #ccc
   .header-right
    min-width: 1.04rem;
    padding: 0 .1rem
    float: right
    text-align: center
    .arrow-icon
      font-size: .2rem;
</style>
