<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      title: "Ecco",
    };
  },

  components: { AppTitle, AppHero },
  
};
</script>

<template>
  <div class="container">
    <h1>{{ title }}</h1>

    <AppTitle></AppTitle>

    <AppHero></AppHero>

  </div>
</template>

<style>
.container {
  margin-left: auto;
  margin-right: auto;
  width: 1000px;
  text-align: center;
}

h1 {
  color: red;
}
</style>
