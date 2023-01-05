<template>
  <h1>Detay sayfa</h1>
  <p>Açıklama sayfası olacaktır burası</p>
  <p>{{ $route.params.userId }}</p>
  <button @click="goBack">Geri Dön</button>
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
