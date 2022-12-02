<template>
  <div class="health-plan">
    <div class="container health">
      <h3
        class="py-5 text-uppercase text-center fw-bolder"
        style="color: #284948"
      >
        HEALTH PLAN
      </h3>
    </div>
    <div class="container-fluid">
      <div class="row healths">
        <div class="col-md px-0 health-color">
          <h2>HEAL</h2>
          <ul class="text-white">
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
          </ul>
        </div>
        <div class="d-none d-md-block blue-circle">
          <div class="text-div">
            <img src="../assets/images/plus.png" alt="" class="img-fluid" />
          </div>
        </div>
        <div class="col-md px-0">
          <img
            src="../assets/images/mountain.png"
            style="width: 100%; height: 100%"
            class="img-fluid"
            alt=""
          />
        </div>
      </div>

      <div class="row healths-check flex-row-reverse">
        <div class="col-md px-0 health-colors">
          <h2>ENGAGE</h2>
          <ul>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
          </ul>
        </div>
        <div class="d-none d-md-block blue-circle white-circle">
          <div class="text-div">
            <img src="../assets/images/plus.png" alt="" class="img-fluid" />
          </div>
        </div>
        <div class="col-md px-0">
          <img
            src="../assets/images/check.png"
            style="width: 100%; height: 100%"
            class="img-fluid"
            alt=""
          />
        </div>
      </div>

      <div class="row healths-exercise">
        <div class="col-md px-0 health-color">
          <h2>STAY</h2>
          <ul class="text-white">
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
            <li>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
              ipsum dolor sit amet consectetur adipisicing elit.
            </li>
          </ul>
        </div>
        <div class="d-none d-md-block blue-circle">
          <div class="text-div">
            <img src="../assets/images/plus.png" alt="" class="img-fluid" />
          </div>
        </div>
        <div class="col-md px-0">
          <img
            src="../assets/images/exercise.png"
            style="width: 100%; height: 100%"
            class="img-fluid"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.health-color {
  background: #284948 !important;
}

.health-color ul,
.health-colors ul {
  padding: 70px;
  padding-top: 20px;
}

.health-color ul li,
.health-colors ul li {
  padding-bottom: 10px;
}

.health-colors h2 {
  color: #284948 !important;
}

.health-color h2,
.health-colors h2 {
  padding-left: 50px;
  padding-top: 30px;
  color: #c3d797;
}

.healths,
.healths-check,
.healths-exercise {
  position: relative;
}

.blue-circle {
  background-color: white;
  border-radius: 50%;
  height: 80px;
  width: 80px !important;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -40px !important;
  margin-left: -40px;
  display: table;
}

.blue-circle .text-div {
  padding-top: 10px;
}

.health-colors {
  background: white;
}

.text-div {
  display: table-cell;
  text-align: center;
  vertical-align: middle;
}

@media only screen and (max-width: 767px) {
  .health-color ul,
  .health-colors ul {
    padding: 35px;
    padding-top: 20px;
  }

  .health-color h2,
  .health-colors h2 {
    padding-left: 25px;
    padding-top: 20px;
  }
}
@media only screen and (max-width: 992px) {
  .health-color ul,
  .health-colors ul {
    padding: 50px;
  }
}
</style>
