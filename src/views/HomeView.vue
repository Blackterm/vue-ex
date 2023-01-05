<template>
  <div class="home"></div>
  <h1>Anasayfa</h1>
  <p>Anasayfa sayfa olacaktır burası</p>
  <input type="text" @keydown.enter="goToDetails" />
</template>

<script>
// @ is an alias to /src
export default {
  name: "HomeView",
  components: {},
  methods: {
    goToDetails(e) {
      this.$router.push(`/detail/${e.target.value}`);
    },
  },
};
</script>
