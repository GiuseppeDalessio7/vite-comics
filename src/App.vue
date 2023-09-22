<script >
import AppHeader from "./components/AppHeader.vue"
import AppLowHead from "./components/AppLowHead.vue"



export default {
  components: {
    AppHeader,
    AppLowHead,
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
  <AppLowHead></AppLowHead>
</template>

<style >
img {
  width: 4rem;
  height: 4rem;
}

body {
  font-family: 'Comic Neue', cursive;
  font-family: 'Open Sans', sans-serif;
}

.mygoes {
  width: 80px;
  height: 80px;

}
</style>
