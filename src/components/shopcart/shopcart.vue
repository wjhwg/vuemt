<template>
  <div>
    <div class="shopcart">
      <div class="content">
        <div class="content-left">
          <div class="logo-wrapper">
            <div class="logo">
              <i class="icon-shopping_cart"></i>
            </div>
            <div class="num"></div>
          </div>
          <div class="price"></div>
          <div class="desc"></div>
        </div>
        <div class="content-right">
          <div class="pay"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/mixin.styl"
  .shopcart
    position fixed
    left 0
    bottom 0
    z-index 50
    width 100%
    height 48px
    background gray
    .content
      display flex
      background #141d27
      font-size: 0
      color: rgba(255, 255, 255, 0.4)

</style>
