<template>
  <div>
    <nav class="front-header bg-dark text-white px-2 pb-3">
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
        <nuxt-link to="verification" class="card text-decoration-none text-dark elevated border-0 mb-3" style="background: #ffe082">
          <div class="card-body verify-octagon" style="padding-left: 4rem">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
            <h6>Akun anda belum diverifikasi</h6>
            <span style="font-size: .85rem">Silahkan lakukan verifikasi dengan klik disini</span>
          </div>
        </nuxt-link>
        <div class="card border-0 elevated">
          <div class="card-body py-3">
            <nuxt-link to="saldo" class="text-dark text-decoration-none">
              <h6>Saldo</h6>
              <h4 class="font-weight-bold m-0"><sup>Rp.</sup> 500.000</h4>
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
.verify-octagon {
  position: relative;
  svg {
    position: absolute;
    left: 1rem;
    width: 34px;
    height: 34px;
    top: calc(50% - 17px);
  }
}
</style>
