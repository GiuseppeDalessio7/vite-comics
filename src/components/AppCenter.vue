<script >
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="mycolorblue">
        <div class="container d-flex p-5 justify-content-between">
            <div class="">
                <img id="imgset" src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span><a href="">digital comics</a></span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span><a href="">merchandise</a></span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span><a href="">subscriptions</a></span>
            </div>
            <div>
                <img id="imgset" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span><a href="">shoplocator</a></span>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span><a href="">dc power visa</a></span>
            </div>
        </div>
    </div>
</template>
  
<style scoped>
.mycolorblue {
    background-color: #0C7DED;
}

span {
    color: white;
    margin-left: 1rem;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 300;
}

img {
    width: 55px;
    height: 55px;
}

#imgset {
    width: 40px;
    height: 55px;
}

a {
    text-decoration: none;
    color: white;
}
</style>
  