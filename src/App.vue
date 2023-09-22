<script >
import AppHeader from "./components/AppHeader.vue"


export default {
  components: {
    AppHeader,
    // AppHero,
  },
  data() {
    return {
      imgLogo: "./assets/img/dc-logo.png",


    }
  }
}
</script>

<template>
  <div class=" container p-3">
    <div class="d-flex justify-content-between">
      <img class="" src="./assets/img/dc-logo.png" alt="">
      <AppHeader></AppHeader>
    </div>
  </div>
</template>

<style scoped>
img {
  width: 4rem;
  height: 4rem;
}

body {
  font-family: 'Comic Neue', cursive;
  font-family: 'Open Sans', sans-serif;
}
</style>
