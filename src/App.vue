<script >
import AppHeader from "./components/AppHeader.vue"
import AppLowHead from "./components/AppLowHead.vue"
import AppCenter from "./components/AppCenter.vue"



export default {
  components: {
    AppHeader,
    AppLowHead,
    AppCenter,
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
  <div>
    <AppCenter></AppCenter>
  </div>
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

.mycolor {
  background-color: #1C1D1D;
}

.mygoes {
  width: 80px;
  height: 80px;

}
</style>
