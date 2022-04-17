<template>
    <section class="mb-5 pt-5 pb-5 border-bottom">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <div class="wrapper w-100 w-lg-75 mb-5 pb-5 mb-lg-0 pb-lg-0">
              <div class="address mb-0 pb-0 mb-lg-5 pb-lg-5">
                <table class="table table-borderless">
                  <tr>
                    <th class="w-50 w-lg-75 fs-5">Industri</th>
                    <th class="w-50 fs-5">Region</th>
                  </tr>
                  <tr>
                    <td class="w-50 w-lg-75 fs-5 text-fade-black-1">Comodity Trading</td>
                    <td class="w-50 fs-5 text-fade-black-1">Europe</td>
                  </tr>
                </table>
              </div>
              <div class="services mt-5 pt-5">
                <h2 class="fs-5 fw-bold text-uppercase mb-5">services used</h2>
                <div class="d-flex flex-wrap">
                  <router-link class="me-2 btn btn-light rounded-pill border-fade-black-1 px-4 py-2 mb-2 text-fade-black-1"
                    to="#">Application
                    Development</router-link>
                  <router-link class="me-2 btn btn-light rounded-pill border-fade-black-1 px-4 py-2 mb-2 text-fade-black-1"
                    to="#">Support</router-link>
                  <router-link class="me-2 btn btn-light rounded-pill border-fade-black-1 px-4 py-2 mb-2 text-fade-black-1"
                    to="#">Application
                    fle-engineering</router-link>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="wrapper w-100">
              <h2 class="fs-5 fw-bold text-uppercase mb-5">the situation</h2>
              <p class="fs-5 text-fade-black-1">
                Since partnering with IXM in 2013. ELEKS has provided standalone, stable IT support and appication
                maintenance services.
              </p>
              <p class="fs-5 text-fade-black-1">
                One of the apps we have been engaged in supporting is SAP Business Objects - a platform that works as a
                BI and reporting tool to enchance the client's internal ERP system. Following an in-depth three-month
                knowledge transfer phase, we provided Lw/L3 support services taht included the development of new
                reports, fixing inconsistencies within existing reporting and support of the platform infrastructure.
              </p>
              <p class="fs-5 text-fade-black-1">
                In April 2019, IXM decided to upgrade their SAP BO platform to a newer version following oyur r=previous
                partnership success - and the deep knowledge our team already had about the system - IXM chose ELEKS to
                carry out the migration
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>

<script>
export default {
  name: "ComodityTradingComponent",
}
</script>