<template>
<div class="work">
    <div class="container working pt-3 pb-5">
        <h3 class="py-5 text-uppercase text-center fw-bolder" style="color: #284948">
            how does this work ?
        </h3>
        <div class="row">
            <div class="col-sm pb-5 pb-sm-0 text-center align-self-center">
                <div class="py-2 h4 fw-normal" style="color:#DD7A1D">
                    Step 1
                </div>
                <div class="py-3 work-data fw-bolder">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
                <div class="line" style="border:1px solid #DD7A1D; width:20%; margin:0 auto;"></div>
                <div class="py-3 work-data fw-normal">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
            </div>

            <div class="col-sm pb-5 pb-sm-0 text-center">
                <div class="py-2 h4 fw-normal" style="color:#DD7A1D">
                    Step 2
                </div>
                <div class="py-3 work-data fw-bolder">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
                <div class="line" style="border:1px solid #DD7A1D; width:20%; margin:0 auto;"></div>
                <div class="py-3 work-data fw-normal">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
                <div class="image-link">
                    <img src="../assets/images/yoga.png" class="img-fluid" alt="">
                </div>
            </div>

            <div class="col-sm pb-5 pb-sm-0 text-center align-self-center">
                <div class="py-2 h4 fw-normal" style="color:#DD7A1D">
                    Step 3
                </div>
                <div class="py-3 work-data fw-bolder">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
                <div class="line" style="border:1px solid #DD7A1D; width:20%; margin:0 auto;"></div>
                <div class="py-3 work-data fw-normal ">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                </div>
                <div class="rq-btn-data">
                    <button class="btn btn-warning reqbtn">REQUEST DEMO</button>
                </div>
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
.work {
    background: #F9F9F9;
}

.image-link img::after {
  font-family: FontAwesome;
  content: "\f3c5";
  color: #f28737;
}

.reqbtn {
    background: #f28737 !important;
    color: white !important;
    border: #f28737 !important;
    font-size: 14px !important;
    font-weight: 400 !important;
}
.reqbtn:hover{
    background:#df670d !important;
    border: #df670d !important;
}
</style>
