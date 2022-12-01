<template>
<div>
    <div class="dashboard-white bg-white">
        <div class="dark-blue-grad">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <div class="laptop">
                            <img src="../assets/images/laptop.png" class="img-fluid" alt="" />
                        </div>
                    </div>
                    <div class="col-6 text-white fs-6">
                        <div class="dashboard-text-data">
                            <div class="dashboard-text">
                                COMPLETE DASHBOARD FOR YOUR COMPANY
                            </div>
                            <button class="btn btn-warning req-btn">request</button>
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
    font-size: 31px;
    font-weight: 500;
    padding: 10% 40% 0% 10%;
}

.req-btn {
    background: #f28737 !important;
    color: white !important;
    /* border: #f28737 !important; */
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
</style>
