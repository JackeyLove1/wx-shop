<script setup lang="ts">

const { safeAreaInsets } = uni.getSystemInfoSync()

</script>

<template>
  <view class="navbar" :style="{paddingTop: safeAreaInsets!.top + 'px'}">
    <view class="logo">
      <image class="logo-image" src="@/static/images/logo.png"></image>
      <div></div>
      <text class="logo-text">新鲜 · 亲民 · 快捷</text>
    </view>
    <view class="search">
      <text class="icon-search">搜索商品</text>
      <text class="icon-scan"></text>
      "
    </view>
  </view>
</template>

<style scoped>
/* 自定义导航条 */
.navbar {
  background-image: url(@/static/images/navigator_bg.png);
  position: relative;
  background-size: cover;
  display: flex;
  flex-direction: column;
}

.logo {
  display: flex;
  flex-direction: row;

}
.logo-image {
  width: 166rpx;
  height: 39rpx;
}
.logo-text {
  font-size: 24rpx;
  color: white;
  margin-left: 20rpx;
}

</style>
