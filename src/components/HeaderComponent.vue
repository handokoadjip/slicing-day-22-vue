<template>
  <header class="mb-5">
    <nav class="navbar navbar-expand-lg navbar-light bg-white px-5">
      <div class="container-fluid">
        <router-link class="navbar-brand text-primary fs-2 fw-medium" to="#">eleks</router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="mx-0 my-5 mx-lg-4 my-lg-0" to="#">About Us</router-link>
            </li>
            <li class="nav-item">
              <router-link class="mx-0 my-5 mx-lg-4 my-lg-0" to="#">Services</router-link>
            </li>
            <li class="nav-item">
              <router-link class="mx-0 my-5 mx-lg-4 my-lg-0" to="#">Industries & Expertise</router-link>
            </li>
            <li class="nav-item">
              <router-link class="mx-0 my-5 mx-lg-4 my-lg-0" to="#">Case Studies</router-link>
            </li>
            <li class="nav-item">
              <router-link class="mx-0 my-5 mx-lg-4 my-lg-0" to="#">Blog</router-link>
            </li>
          </ul>
          <div class="d-flex align-items-center d-none d-lg-flex">
            <router-link class="mx-3 btn btn-light rounded-pill border-fade-black-1 px-4 py-2" to="#">Contact Us
            </router-link>
            <i class="mx-3 fas fa-search"></i>
            <p class="mx-3 mb-0">EN</p>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

