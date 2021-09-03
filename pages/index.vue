<template>
  <div>
    <nav class="front-header bg-dark text-white px-2">
      <div class="container py-3">
        <img src="https://tdev.kiriminaja.com/assets/atrust/svg-logo.svg" class="mb-4" height="40px" alt="">
        <div class="row">
          <div class="col">
            <div class="row no-gutters">
              <div class="col-auto">
                <img src="https://kiriminaja.com/storage/Users/Juni2021/985_29_02-50-19.jpg" style="border: 2px solid #fff; border-radius: 40px" width="40px" height="40px" alt="">
              </div>
              <div class="col pl-3">
                <h5 class="font-weight-bold">Fariz Gustanjung</h5>
                <span>082243374043</span>
              </div>
            </div>
          </div>
          <div class="col-auto"></div>
        </div>
      </div>
    </nav>
    <section class="balance-section">
      <div class="container">
        <div class="card border-0 elevated">
          <div class="card-body py-3">
            <nuxt-link to="saldo" class="text-dark text-decoration-none">
              <h6>Saldo</h6>
              <h4 class="font-weight-bold"><sup>Rp.</sup> 500.000</h4>
            </nuxt-link>
          </div>
          <div class="card-body" style="border-top: 1px solid rgba(0,0,0,.09)">
            <div class="row">
              <div class="col-4">
                <a href="" class="text-center link-fluid">
                  <img class="img-fluid" src="~/assets/delivery-truck.png" alt="Paketku">
                  <span>Kirimin</span>
                </a>
              </div>
              <div class="col-4">
                <nuxt-link to="package" class="text-center link-fluid">
                  <img class="img-fluid" src="~/assets/clock.png" alt="Paketku">
                  <span>Paketku</span>
                </nuxt-link>
              </div>
              <div class="col-4">
                <a href="" class="text-center link-fluid">
                  <img class="img-fluid" src="~/assets/package.png" alt="Paketku">
                  <span>CekAja</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped lang="scss">
.balance-section {
  position: relative;
  &::before {
    content: "";
    height: 50%;
    background: var(--dark);
    width: 100%;
    position: absolute;
    border-radius: 0 0 1rem 1rem;
  }
}
.link-fluid {
  display: block;
  color: var(--dark);
  text-decoration: none;
  img {
    width: 50px;
    height: 50px;
    margin: 0 auto;
  }
  span {
    display: block;
  }
}
</style>
