<template>
<div>
    <div class="dashboard-white bg-white">
        <div class="dark-blue-grad">
            <div class="container">
                <div class="row flex-column-reverse flex-md-row flex-row py-2">
                    <div class="col-12 col-md-6">
                        <div class="laptop">
                            <img src="../assets/images/laptop.png" class="img-fluid" alt="" />
                        </div>
                    </div>
                    <div class="col-12 col-md-6 text-white fs-6">
                        <div class="dashboard-text-data text-center text-md-start">
                            <div class="dashboard-text fs-2 pb-4">
                                COMPLETE DASHBOARD FOR YOUR COMPANY
                            </div>
                            <button class="btn btn-warning req-btn p-2">
                                REQUEST DEMO
                            </button>
                        </div>
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
.dashboard-text {
    /* font-size: 31px; */
    font-weight: 500;
    line-height: 114%;
}

.dashboard-text-data {
    padding: 10% 40% 0% 10%;
}

.req-btn {
    background: #f28737 !important;
    color: white !important;
    border: #f28737 !important;
    font-size: 11px !important;
    font-weight: 400 !important;
}

.dashboard-white {
    height: 460px;
    background: #fff;
}

.dark-blue-grad {
    height: 270px;
    background: linear-gradient(90.05deg, #284948 1.22%, #141414 98.84%);
}

@media only screen and (max-width: 767px) {
    .dashboard-text-data {
        padding: 10% 5% 10% 5%;
        text-align: center
    }
    .laptop{
        text-align: center;
    }
    .laptop img{
        max-width: 55%;
    }

}
</style>
