<script>
export default {
  data() {
    return {
      immagine: "01.webp",
    };
  },

  methods: {
    getImagePath(nameFileImg) {
      const imgUrl = new URL("../assets/img/" + nameFileImg, import.meta.url);

      return imgUrl.href;
    },
  },
};
</script>

<template>
  <div class="card-img">
    <img :src="getImagePath(immagine)" alt="" />
  </div>
</template>

<style scoped>
.card-img {
  width: 100%;
}

img {
  width: 50%;
}
</style>
