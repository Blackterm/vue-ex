<template>
  <div class="containers">
    <router-link to="/" class="deneme" active-class="active"
      >Anasayfa</router-link
    >
    <router-link to="/about" class="deneme" active-class="active"
      >Hakkımda</router-link
    >
    <router-view></router-view>
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

.murat {
  background-color: grey;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
