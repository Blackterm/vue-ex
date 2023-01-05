<template>
  <app-header />
  <div class="flex flex-row">
    <SideBar />
    <router-view></router-view>
  </div>
</template>
<script>
import SideBar from "@/components/sideBar.vue";
export default {
  components: {
    SideBar,
  },
};
</script>
HomeView

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
