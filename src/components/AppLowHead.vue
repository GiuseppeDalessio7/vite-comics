<script >
import comics from "../comics.js";
export default {
    name: 'AppLowHead',
    data() {
        return {
            comics: comics
        }
    }
}
</script>

<template>
    <div class="mycolor">
        <div class="container">
            <button id="btncurrent" type="button" class="btn btncolor ">CURRENT SERIES</button>
        </div>
        <div class="container d-flex">
            <div class="row cols-1 row-cols-sm-6">
                <div class="col" v-for="card in comics">
                    <div id="mycolor" class="card pt-4">
                        <img :src="card.thumb" alt="">
                        <p class="text-white py-4 size_font ">{{ card.series }}</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center pb-3">
            <button type="button" class="btn btncolor ">LOAD MORE</button>
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

.size_font {
    font-size: 12px;
    text-transform: uppercase;
}
</style>
  