<template>
  <div class="wrapper">
    <div class="position">
      <span class="iconfont icon-position position__icon">苏州市虎丘区昆仑山路58号中移软件园啥啥啥赛赛赛赛</span>
      <span class="iconfont icon-notice notice__icon"/>
    </div>
  </div>
  <div class="docker">
    <div class="docker__item docker__item--active">
      <div class="iconfont icon-home"></div>
      <div class="docker__title">首页</div>
    </div>
    <div class="docker__item docker__item--active">
      <div class="iconfont icon-cart "></div>
      <div class="docker__title">购物车</div>
    </div>
    <div class="docker__item docker__item--active">
      <div class="iconfont icon-order"></div>
      <div class="docker__title">订单</div>
    </div>
    <div class="docker__item docker__item--active">
      <div class="iconfont icon-my"></div>
      <div class="docker__title">我的</div>
    </div>
  </div>
</template>

<style lang="stylus">
.wrapper
  position absolute
  left 0
  top 0
  bottom 0.5rem
  right 0
  padding 0 0.18rem

  .position
    position relative
    overflow hidden
    text-overflow ellipsis
    white-space nowrap
    padding 0.16rem 0.24rem 0.16rem 0
    line-height 0.22rem
    font-size 0.16rem
    width 100%

    .position__icon
      position relative
      font-size 0.2rem

    .notice__icon
      position absolute
      font-size .2rem
      right 0
      padding  0 0.2rem

.docker
  display flex
  position absolute
  box-sizing border-box
  padding 0 0.18rem
  left 0
  bottom 0
  width 100%
  height 0.49rem
  border-top 0.01rem solid #F1F1F1

  .docker__item
    flex 1
    text-align center

    .iconfont
      margin 0.07rem 0 0.02rem 0
      font-size 0.18rem

  .docker__item--active
    color #1FA4FC

  .docker__title
    font-size 0.12rem
</style>
