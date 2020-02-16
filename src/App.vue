<template>
  <div id="app">
    <h1>你能看到这些文字吗？</h1>
    <p>我们无意中发现一个特殊的网站 favicon 设置会导致微信 7.0.10 WebView 全面崩溃</p>
    <p>而出现崩溃的机型集中在华为特定型号</p>
    <p>这些手机不但无法访问本网站，甚至在访问本网站之后无法打开任何其他网站</p>
    <p>这个网站只是一个 vue-cli 创建的模板项目，除了一些文字展示没有其他任何逻辑</p>
    <p>我们把项目源码放置在：https://github.com/Wolf-Tungsten/wawei-crash</p>
    <p>希望有人能够解释其中的原理</p>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
