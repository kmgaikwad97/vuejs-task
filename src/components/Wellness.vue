<template>
<div class="wellness-bg">
    <div class="container py-0 py-sm-5">
        <div class="row">
            <div class="col-md pt-5">
                <div class="wellness-head pb-4">
                    <div class="h4 fw-bolder">
                        HOLISTIC WELLNESS:
                    </div>
                    <div class="h4 fw-normal">
                        NATURAL THERAPIES IDENTIFY THE ROOT CAUSE
                    </div>
                </div>
                <ul class="welness-text">
                    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi earum, non tempore ipsam eum consectetur odio ratione, hic facilis explicabo neque sequi, reiciendis sed recusandae!</li>
                    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi earum, non tempore ipsam eum consectetur odio ratione, hic facilis explicabo neque sequi, reiciendis sed recusandae!</li>
                </ul>
            </div>

            <div class="col-md">
                <h3 class="py-5 text-uppercase text-center fw-bolder" style="color: #284948">
                    6 DIMENSIONS OF WELLNESS
                </h3>
                <!--  -->
                <div class="wellness-data row me-n1 me-md-3 mb-4">
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/meditation.png" style="width:50%" alt="">
                        </div>
                        <span>Spiritual</span>
                    </div>
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/environment.png" style="width:50%" alt="">
                        </div>
                        <span>Environmental</span>
                    </div>
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/psychology.png" style="width:50%" alt="">
                        </div>
                        <span>Emotional</span>
                    </div>
                </div>
                <!--  -->
                <!--  -->
                <div class="wellness-datas row ms-n1 ms-md-3 mb-1">
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/meditation.png" style="width:50%" alt="">
                        </div>
                        <span>Spiritual</span>
                    </div>
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/environment.png" style="width:50%" alt="">
                        </div>
                        <span>Environmental</span>
                    </div>
                    <div class="col mx-lg-3 mx-0 natural-box text-center">
                        <div class="bottle-medicine p-3 text-center text-align-center rounded">
                            <img src="../assets/images/psychology.png" style="width:50%" alt="">
                        </div>
                        <span>Emotional</span>
                    </div>
                </div>
                <!--  -->
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.wellness-bg {
    background: #FBFEE9;
    color: #284948;
}

.welness-text li {
    padding-bottom: 10px;
}

.bottle-medicine {
    background: #41345F;
    height: 75%;
}

.natural-box:nth-child(2) .bottle-medicine {
    background: linear-gradient(180deg, #44965B 0%, #3E8C58 100%);
}

.natural-box:nth-child(3) .bottle-medicine {
    background: #DD7A1D;
}

.natural-box span {
    font-size: 80%;
}

@media only screen and (max-width: 576px) {
    /* .wellness-data{
        margin-right: 0%;
    }
    .wellness-datas{
        margin-left: 0%;
    } */
}
</style>
