<template>
  <div class="tab">
    <router-link tag="div" class="tab-item" to="/HomePage">
      <div class="tab-icon">
        <img src="../../images/HomePage/u547.png" height="22" width="33"/>
      </div>
      <span class="tab-link">首页</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/HomeWorkOrder">
      <div class="tab-icon">
        <img src="../../images/HomePage/u539.png" height="22" width="33"/>
      </div>
      <span class="tab-link">工单</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/HomeOrder">
      <div class="tab-icon">
        <img src="../../images/HomePage/u539.png" height="22" width="33"/>
      </div>
      <span class="tab-link">订单</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/HomeMine" style="border-right: none">
      <div class="tab-icon">
      <img src="../../images/HomePage/u539.png" height="22" width="33"/>
      </div>
      <span class="tab-link">我的</span>
    </router-link>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {};
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  .tab
    position: fixed
    width: 100%
    bottom: 0
    border-top: 1px solid #e4e4e4
    display: flex
    height: 46px
    font-size: 12px
    background-color white
    z-index 1
    .tab-item
      flex: 1
      text-align: center
      display: flex
      flex-direction: column
      align-items: center
      justify-content: center
      border-right 1px solid #e4e4e4
      .tab-link
        font-size: 12px
      &.router-link-active
        .tab-link
          color: #4CD963
</style>
