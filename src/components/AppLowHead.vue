<script >
import comics from "";
export default {
    name: 'AppLowHead',
    data() {
        return {
            comics: allCard
        }
    }
}
</script>

<template>
    <div class="mycolor">
        <div class="container text-white d-flex align-items-center">
            <div class="row cols-1 row-cols-sm-3">
                <div class="col" v-for="card in comics">
                    <div class="card card ">
                        <img :src="card.thumb" alt="" class="card-img-top">
                    </div>

                </div>

            </div> INSERIRE IMMAGINI DINAMICAMENTE
            <p class=" mygoes"> </p>
        </div>
    </div>
</template>
  
<style></style>
  