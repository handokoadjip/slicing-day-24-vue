<template>
  <header class="min-vh-100 position-relative">
    <nav class="navbar navbar-expand-lg fixed-top navbar-light px-4">
      <div class="container-fluid px-0">
        <router-link class="navbar-brand me-5 d-none d-lg-block" to="#">
          Cloudy and 13C Mantheim
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">journal</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="wrapper text-center">
            <div class="position-absolute top-50 start-50 translate-middle">
              <h1 class="display-4 px-5 fw-bolder text-uppercase ls-5px">
                dennis adelmann
              </h1>
              <small class="fs-4 ls-5px">communication design</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

