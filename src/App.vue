<script>
import AppTitle from "./components/AppTitle.vue";

export default {
  data() {
    return {
      title: "Ecco",
    };
  },

  components: { AppTitle },
};
</script>

<template>
  <div class="container">
    <h1>{{ title }}</h1>

    <AppTitle></AppTitle>

  </div>
</template>

<style s>
.container{
    margin-left:auto;
    margin-right: auto;
    width: 1000px;
    text-align: center;
}

h1 {
  color: red;
}
</style>
