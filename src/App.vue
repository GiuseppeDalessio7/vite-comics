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
  <img src="./assets/img/dc-logo.png" alt="">
  <AppHeader></AppHeader>
</template>

<style scoped></style>
