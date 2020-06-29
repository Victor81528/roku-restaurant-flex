<template>
  <div id="app">
    <div class="nav">
      <div class="nav-tittle">
        <h1>六角西餐廳</h1>
      </div>
        <ul class="nav-list">
          <li><a href="">特色</a></li>
          <li><a href="">主廚</a></li>
          <li><a href="">地圖</a></li>
        </ul>
    </div>
    <div class="banner">
      <div class="banner-content">
        <h1>咬一口就無法忘懷的漢堡</h1>
        <p>七夕絕對無法錯過的好滋味</p>
        <p>六角大漢堡</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import 'scss/all.scss';
.nav {
  a {
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
