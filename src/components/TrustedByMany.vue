<template>
  <div>
    <div class="container py-5 px-md-3 px-5 text-center">
      <h3 class="py-4 text-uppercase" style="color: #284948">
        Trusted By Many
      </h3>
      <div class="trust-box py-4 row">
        <!-- <div class="trust-once col col-sm mx-md-3 my-4 mx-0"> -->
        <div class="trust-once col col-sm my-4 mx-0">
          <div class="text-align-center p-4 trusted-colors">DummyText</div>
        </div>
        <!-- <div class="trust-once col col-sm mx-md-3 my-4 mx-0"> -->
        <div class="trust-once col col-sm my-4 mx-0">
          <div class="text-align-center p-4 trusted-colors">DummyText</div>
        </div>
        <!-- <div class="trust-once col col-sm mx-md-3 my-4 mx-0"> -->
        <div class="trust-once col col-sm my-4 mx-0">
          <div class="text-align-center p-4 trusted-colors">DummyText</div>
        </div>
        <!-- <div class="trust-once col col-sm mx-md-3 my-4 mx-0"> -->
        <div class="trust-once col col-md-3 mx-md-3 my-4 mx-0">
          <div class="text-align-center p-4 trusted-colors">DummyText</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* .trust-box .trust-once .trusted-colors:nth-child(1),.trust-box .trust-once .trusted-colors:nth-child(2),.trust-box .trust-once .trusted-colors:nth-child(3),.trust-box .trust-once .trusted-colors:nth-child(4){
    background: #284948;
    height:90px;
}
.trust-box .trust-once .trusted-colors:nth-child(2){
    background: #DD7A1D;
}
.trust-box .trust-once .trusted-colors:nth-child(3){
    background: #3E8C58;
}
.trust-box .trust-once .trusted-colors:nth-child(4){
    background: #41345F;
} */

.trust-box .trust-once:nth-child(1) .trusted-colors,
.trust-box .trust-once:nth-child(2) .trusted-colors,
.trust-box .trust-once:nth-child(3) .trusted-colors,
.trust-box .trust-once:nth-child(4) .trusted-colors {
  height: 90px;
}
.trust-box .trust-once:nth-child(1) .trusted-colors {
  background: #284948;
}
.trust-box .trust-once:nth-child(2) .trusted-colors {
  background: #dd7a1d;
}
.trust-box .trust-once:nth-child(3) .trusted-colors {
  background: #3e8c58;
}
.trust-box .trust-once:nth-child(4) .trusted-colors {
  background: #41345f;
}
</style>