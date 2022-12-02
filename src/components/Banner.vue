<template>
  <div class="banner-data">
    <!-- <div class="banner businessman-img">
      <div style="padding-left: 0px" class="text-uppercase banner-text">
        <p class="text-dta">LOOK AFTER THE PEOPLE,</p>
        <p>WHO LOOK AFTER YOUR BUSINESS.</p>

        <div class="health-wellness">
          <h4 class="text-uppercase">Health Wellness</h4>
          <button class="text-uppercase btn btn-danger">request demo</button>
        </div>
      </div>
    </div> -->
    <div class="position-relative d-flex m-0 bg-img">
      <div class="head-content position-absolute pt-3">
        <div class="head-data pb-3 pb-sm-5">
          <div class="h4 head-size fw-light">LOOK AFTER THE PEOPLE,</div>
          <div class="h4 head-size fw-light">WHO LOOK AFTER YOUR BUSINESS.</div>
        </div>
        <div class="head-title pb-3 pb-sm-4 ">
          <div class="h4 fw-normal">HEALTH WELLNESS.</div>
        </div>
        <div class="head-btn">
          <button class="btn btn-warning btn-sm reqbtn">REQUEST DEMO</button>
        </div>
      </div>
      <div class="head-imgs pt-3" style="width:100%;">
        <img src="../assets/images/businessman.png" style="width:100%" class="img-fluid" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.reqbtn {
  background: #f28737 !important;
  color: white !important;
  border: #f28737 !important;
  /* font-size: 11px !important;
    font-weight: 400 !important; */
}
.head-content{
  position:absolute;
  top:15%;
  left:14%;
}
.banner-data{
  color:#284948;
}




@media only screen and (max-width: 576px) {
    .head-imgs{
      height:250px !important;
    }
    .head-imgs img{
      height: 100% !important;
    }
    .head-content{
      left:10%
    }
    .head-data .head-size{
      font-size:70%
    }

    .head-title div{
      font-size: 16px;
    }
    .reqbtn{
      font-size:small
    }
}

</style>
