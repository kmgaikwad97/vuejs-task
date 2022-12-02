<template>
  <div id="app">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->

    <!-- navbar starts -->
    <nav
      class="navbar navbar-expand-lg bg-light navbar-light shadow rounded p-3"
    >
      <div class="container-fluid">
        <a class="navbar-brand" href="#"></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#"
                >Our Products</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">For Engineers</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Multi-Vitamins</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Buy</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-2 ms-2" href="#">Books</a>
            </li>
            <li class="nav-item">
              <button type="button" class="btn sign-in-btn btn-secondary">
                Sign in/Sign up
              </button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- navbar ends -->

    <router-view />
  </div>
</template>

<style>
.sign-in-btn{
  background: #DCDCDC !important;
  color: black !important;
    border: #DCDCDC !important;
    /* font-size: 11px !important; */
    font-weight: 300 !important;
}

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
/* body {
  min-height: 100%;
  background: url(./assets/images/businessman.png);
  background-size: cover;
  background-repeat: no-repeat;
} */
</style>
