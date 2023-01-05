<template>
  <div class="containers">
    <h1>Detay sayfa</h1>
    <p>Açıklama sayfası olacaktır burası</p>
    <p>{{ $route.params.userId }}</p>
    <button class="containerButton" @click="goBack">Geri</button>
  </div>
</template>
<script>
// @ is an alias to /src

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "detail",
  components: {},
  created() {
    console.log(this.$route);
  },
  methods: {
    goBack() {
      this.$router.push("/");
    },
  },
};
</script>

<style>
.containerButton {
  margin-top: 20px;
  margin-left: auto;
  margin-right: auto;
  width: 50px;
  height: 25px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: center;
}
</style>
