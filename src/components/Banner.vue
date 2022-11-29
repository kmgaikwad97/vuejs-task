<template>
  <div>
    <div class="banner businessman-img">
      <div style="padding-left: 0px" class="text-uppercase banner-text">
        <p class="text-dta">LOOK AFTER THE PEOPLE,</p>
        <p>WHO LOOK AFTER YOUR BUSINESS.</p>

        <div class="health-wellness">
          <h4 class="text-uppercase">Health Wellness</h4>
          <button class="text-uppercase btn btn-danger">request demo</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.businessman-img {
  background: url(../assets/images/businessman.png);
  background-color: #ffffff;
  height: 500px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
.banner-text{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-130%, -60%);
  /* color: white; */
}
</style>