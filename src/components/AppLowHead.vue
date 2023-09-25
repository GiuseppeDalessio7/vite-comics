<script >
import comics from "../comics"
import currentSeries from "../components/currentSeries.vue";
export default {
    name: 'AppLowHead',
    components: {
        currentSeries
    },
    data() {
        return {
            comics
        }
    }
}
</script>

<template>
    <div class="mycolor">
        <div class="container">
            <button id="btncurrent" type="button" class="btn btncolor">CURRENT SERIES</button>
        </div>
        <div class="container d-flex">
            <div class="row cols-1 row-cols-sm-6">

                <currentSeries :img="comics.thumb" :nomeSerie="comics.series" :prezzo="comics.price"
                    v-for="comics in comics">
                </currentSeries>
                <!-- <div class="col" v-for="card in comics"> -->
                <!-- <div id="mycolor" class="card pt-4"> -->
                <!-- <img :src="card.thumb" alt=""> -->
                <!-- <p class="text-white py-4 size_font ">{{ card.series }}</p> -->
                <!-- </div> -->
                <!-- </div> -->
            </div>
        </div>
        <div class="text-center pb-3 pt-2">
            <button type="button" class="btn btncolor ">LOAD MORE</button>
        </div>
    </div>
</template>
  
<style scoped>
#btncurrent {
    margin-top: -30px;
    margin-left: -10px;
    font-weight: bolder;
    font-size: 20px;
    width: 250px;
}

.btncolor {
    background-color: #0C7DED;
    color: white;
    width: 200px;
    border-radius: 0%;
}
</style>
  