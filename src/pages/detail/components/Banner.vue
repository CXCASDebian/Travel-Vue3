<template>
  <div>
    <div class="banner">
      <img
        class="banner-img"
        src="" alt="">
        <div class="banner-info">
          <div class="banner-title">
            this.sightName
          </div>
          <div class="banner-number">
            <span class="iconfont banner-icon">&#xe692;</span>
            this.bannerImgs.length
          </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'DetailBanner'
}
</script>

<style lang="stylus" scoped>
  .banner
    position: relative
    overflow: hidden
    height: 0
    padding-bottom: 55%
    .banner-img
      width: 100%
    .banner-info
      text-align: left
      display: flex
      position: absolute
      left: 0
      right: 0
      bottom: 0
      line-height: .6rem
      color #fff
      background-image: linear-gradient(to top, rgba(0,0,0,0), rgba(0,0,0,0.8) )
      .banner-title
        flex: 1
        font-size: .32rem
        padding: 0 .2rem
      .banner-number
        margin-top: .14rem
        padding: 0 .32rem
        line-height: .32rem
        height: .4rem
        border-radius: .2rem
        background: rgba(0, 0, 0, .8)
        font-size: .24rem
        .banner-icon
          font-size: .24rem

</style>
