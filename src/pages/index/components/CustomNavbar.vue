<script setup lang="ts">

const {safeAreaInsets} = uni.getSystemInfoSync();

</script>

<template>
  <view class="navbar" :style="{paddingTop: safeAreaInsets!.top + 'px'}">
    <view class="logo">
      <image class="logo-image" src="@/static/images/logo.png"></image>
      <text class="logo-text">新鲜 · 亲民 · 快捷</text>
    </view>
    <view class="search">
      <text class="icon-search">搜索商品</text>
      <text class="icon-scan"></text>"
    </view>
  </view>
</template>

<style scoped lang="scss">
.navbar{
  background-image: url("@/static/images/navigator_bg.png");
}
</style>
