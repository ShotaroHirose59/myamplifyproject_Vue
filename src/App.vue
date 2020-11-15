<template>
  <div id="app">
    <div id="nav">
      <li><router-link to="/ai">AIアプリ</router-link></li>
      <li><router-link to="/chat">チャットアプリ</router-link></li>
      <li><router-link to="/analytics">分析アプリ</router-link></li>
      <li><router-link to="/webpush">Web Pushアプリ</router-link></li>
      <router-view />
    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
