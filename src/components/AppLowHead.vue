<script >
import miniCard from "../miniCard"
export default {
    data() {
        return {
            miniCard: miniCard
        }
    }
}
</script>

<template>
    <div class="mycolor">
        <div class="container text-white d-flex align-items-center">
            <div class="row cols-1 row-cols-sm-3">
                <div class="col" v-for="card in miniCard">
                    <div class="card thumb">
                        <img :src="card.thumb" alt="" class="card-img-top">

                    </div>

                </div>

            </div> INSERIRE IMMAGINI DINAMICAMENTE
            <p class=" mygoes"> </p>
        </div>
    </div>
</template>
  
<style></style>
  