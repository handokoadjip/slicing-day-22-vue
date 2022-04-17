<template>
  <footer class="my-3 py-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 order-1 order-lg-10 mb-5 mb-lg-0">
          <div class="wrapper">
            <p class="fs-5">
              Ready to see <br /> what we can do for you?
            </p>
            <p class="fs-1 fw-bold text-primary d-flex align-items-center">
              Contact Us
              <router-link class="text-primary" to="#">
                <i class="fas fa-chevron-circle-right ms-3"></i>
              </router-link>
            </p>
          </div>
        </div>
        <div class="col-lg-6 order-0 order-lg-1 mb-5 mb-lg-0">
          <div class="wrapper">
            <div class="d-flex align-items-center">
              <figure class="m-0">
                <img class="rounded-circle wh-profile me-4" src="@/assets/source/image/img-2.jpg" alt="image-2">
                <div class="text fw-bold fs-5">
                  <p class="mb-0">Romain Desigau</p>
                  <p class="mb-0">Head of IT, IXM</p>
                </div>
              </figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>