<template>
  <div class="nav-bottom">
    <router-link to="/home">
      <i class="iconfont icon-code"></i>
      <label>首页</label>
    </router-link>
    <router-link to="/find">
      <i class="iconfont icon-editor"></i>
      <label>发现</label>
    </router-link>
    <router-link to="/order">
      <i class="iconfont icon-gift"></i>
      <label>订单</label>
    </router-link>
    <router-link to="/my">
      <i class="iconfont icon-QRcode"></i>
      <label>我的</label>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "NavBottom"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
