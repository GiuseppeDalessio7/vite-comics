<script >
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="mycolor">
        <div class="container p-3">
            <div class="d-flex  justify-content-between align-items-center">
                <div class="align-items-center">
                    <button> <span>SIGN UP NOW!</span></button>
                </div>
                <div class="conteiner d-flex gap-3 p-2 m-2 ">

                    <span class="text-primary p-1">FOLLOW US</span>
                    <img src="../assets/img/footer-facebook.png" alt="" srcset="">
                    <img src="../assets/img/footer-twitter.png" alt="" srcset="">
                    <img src="../assets/img/footer-youtube.png" alt="" srcset="">
                    <img src="../assets/img/footer-pinterest.png" alt="" srcset="">
                    <img src="../assets/img/footer-periscope.png" alt="" srcset="">

                </div>
            </div>
        </div>
    </div>
</template>
  
<style scoped>
.mycolor {
    background-color: #313031;
}

img {
    width: 30px;
    height: 30px;
}

button {
    border: 1px solid #0C7DED;
    color: white;
    background-color: transparent;
    padding: 10px;
}

span {
    font-size: 15px;
}
</style>
  