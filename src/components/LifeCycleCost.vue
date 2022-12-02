<template>
<div>
    <div class="life-cycle-cost">
        <div class="container life-cyle">
            <h3 class="py-5 text-uppercase text-center fw-bolder" style="color: #284948">
                LIFECYCLE COST OF A DISEASE
            </h3>

            <div class="row py-5">
                <div class="col-md px-0 text-center">
                    <div class="disease-data">
                        <img src="../assets/images/tablets.png" class="img-fluid" alt="" />
                        <span class="data1 text-light">Direct Cost</span>
                        <!-- <div class="overlay"></div> -->
                    </div>
                    <div class="disease-text">Healthcare & Mediacal Cost</div>
                </div>
                <div class="col-md px-0 pt-3 signs text-center align-self-center pb-5">
                    +
                </div>
                <div class="col-md px-0 text-center">
                    <div class="disease-data">
                        <img src="../assets/images/tabs.png" class="img-fluid" alt="" />
                        <span class="data2 text-light">InDirect Cost</span>
                        <!-- <div class="overlay"></div> -->
                    </div>
                    <div class="disease-text">
                        Decrease Quality of life, pain anxiety, inconvenience &
                    </div>
                </div>
                <div class="col-md px-0 pt-3 signs text-center align-self-center pb-5">
                    +
                </div>
                <div class="col-md px-0 text-center">
                    <div class="disease-data">
                        <img src="../assets/images/medical.png" class="img-fluid" alt="" />
                        <span class="data3 text-light">Intangible Cost</span>
                        <!-- <div class="overlay"></div> -->
                    </div>
                    <div class="disease-text">
                        Decrease quality of life, pain, anxiety, incovenience &
                    </div>
                </div>
                <div class="col-md px-0 pt-3 signs text-center align-self-center pb-5">
                    =
                </div>
                <div class="col-md-3 px-0 text-center">
                    <div class="disease-data">
                        <img src="../assets/images/money.png" class="img-fluid" alt="" />
                        <span class="data4 text-light">Total Cost</span>
                        <!-- <div class="overlay"></div> -->
                    </div>
                    <div class="disease-text">
                        Decrease quality of life, pain, anxiety, incovenience &
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {};
</script>

<style>
.disease-data {
    position: relative;
    /* background: rgba(0, 0, 0, 0.9); */
    /* border-radius: 12%; */
}

.signs {
    color: #3a3b3c;
    font-size: 35px;
}

.disease-text {
    padding-top: 10px;
    font-size: 13px;
    text-align: center;
}

.overlay {
    position: absolute;
    background-color: rgba(0, 0, 0, 0.6);
    width: 100%;
    height: 100%;
    top: 0%;
    border-radius: 11%;
}

.disease-data img {
    position: relative;
    background: rgba(0, 0, 0, 0.7);
    border-radius: 11%;
    filter: brightness(0.5);
}

.disease-data span {
    position: absolute;
    top: 47%;
    right: 28%;
    z-index: 100;
}

.disease-data .data2 {
    right: 24%;
}

.disease-data .data3 {
    right: 17%;
}

.disease-data .data4 {
    right: 39%;
}

.life-cycle-cost {
    background: url("../assets/images/office.png");
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
}

@media only screen and (max-width: 767px) {
    .disease-data span {
        position: absolute;
        top: 47%;
        right: 42%;
        z-index: 100;
    }

    .disease-data .data2 {
        right: 40%;
    }

    .disease-data .data3 {
        right: 40%;
    }

    .disease-data .data4 {
        right: 43%;
    }
}
</style>
