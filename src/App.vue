<script setup>
</script>

<template>
  <div id="app">
    <nav>
      <router-link to="/">首页</router-link>
      <router-link to="/about">关于</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<style>
nav {
  padding: 20px;
  background: #f0f0f0;
  margin-bottom: 20px;
}

nav a {
  margin-right: 20px;
  text-decoration: none;
  color: #333;
}

nav a.router-link-active {
  color: #42b983;
  font-weight: bold;
}
</style>