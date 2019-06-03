<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home1</router-link>|
      <router-link to="/about">About1</router-link>
    </div>
    <div>
      <p><a href="/page1.html" target="_blank">跳转新的页面page1</a></p>
			<p><a href="/page2.html" target="_blank">跳转新的页面page2</a></p>
			<p><a href="/page1.html#/about" target="_blank">跳转page1的子路由页面</a></p>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
