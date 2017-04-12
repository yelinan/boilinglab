<template>
<div id="app">
  <header>
    <div class="container clear">
      <a href="" class="logo">
        <img src="./assets/logo.jpg" alt="Boiling Lab">
      </a>
      <nav class="small_nav">
        <ul>
          <li class="">

          </li>
        </ul>
      </nav>
    </div>
  </header>
  <router-view></router-view>
</div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
body {
  background: #201D1E;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
