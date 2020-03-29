<template>
  <div id="app">
    <!-- 路由展示 -->
    <router-view />

    <!-- 底部导航 -->
    <div class="nav-botton">
      <router-link to="/home">
        <label>首页</label>
      </router-link>
      <router-link to="/find">
        <label>发现</label>
      </router-link>
      <router-link to="/order">
        <label>订单</label>
      </router-link>
      <router-link to="/my">
        <label>我的</label>
      </router-link>
    </div>
  </div>
</template>

<style>
/* @import './assets/css/index.css' */
</style>
