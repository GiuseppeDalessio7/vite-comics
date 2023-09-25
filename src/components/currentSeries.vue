<script >
export default {
    name: "serieTv",
    props: ["img", "prezzo", "nomeSerie", "tipo"]
}
</script>

<template>
    <div class="col">
        <div id="mycolor" class="card pt-4">
            <img class="img-fluid" :src="img" alt="">
            <p class="text-white w-100 pt-3 size_font ">{{ nomeSerie }}</p>
            <!-- <p class="text-white w-100 h-50 ">{{ prezzo }}</p> -->
        </div>
    </div>
</template>
  
<style scoped>
img {
    width: 200px;
    height: 200px;
}

#mycolor {
    background-color: #1C1D1D;
}

.size_font {
    font-size: 12px;
    text-transform: uppercase;
}
</style>
  