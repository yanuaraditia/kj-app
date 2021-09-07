<template>
  <div>
    <nav class="front-header bg-dark text-white px-2 pb-1">
      <div class="page-header">
        <div class="container py-3">
          <img src="https://tdev.kiriminaja.com/assets/atrust/svg-logo.svg" class="mb-4" height="40px" alt="">
          <div class="row">
            <div class="col">
              <nuxt-link class="text-decoration-none text-white" to="account">
                <div class="row no-gutters">
                  <div class="col-auto d-flex align-items-center">
                    <img src="https://kiriminaja.com/storage/Users/Juni2021/985_29_02-50-19.jpg" style="border: 3px solid #fff; border-radius: 40px" width="50px" height="50px" alt="">
                  </div>
                  <div class="col pl-3">
                    <h5 class="font-weight-bold">Fariz Gustanjung</h5>
                    <span>082243374043</span>
                  </div>
                </div>
              </nuxt-link>
            </div>
            <div class="col-auto"></div>
          </div>
        </div>
      </div>
    </nav>
    <section class="balance-section">
      <div class="container">
<!--        <nuxt-link to="verification" class="card text-decoration-none text-dark elevated border-0 mb-3" style="background: #ffe082">-->
<!--          <div class="card-body verify-octagon" style="padding-left: 4rem">-->
<!--            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>-->
<!--            <h6>Akun anda belum diverifikasi</h6>-->
<!--            <span style="font-size: .85rem">Silahkan lakukan verifikasi dengan klik disini</span>-->
<!--          </div>-->
<!--        </nuxt-link>-->
        <div class="card border-0 elevated">
          <div class="card-body py-3">
            <nuxt-link to="saldo" class="text-dark text-decoration-none">
              <h6>Saldo</h6>
              <h4 class="font-weight-bold m-0">Rp. 500.000</h4>
              <span style="font-size: .85rem">Estimasi Rp. 30.000.000</span>
            </nuxt-link>
          </div>
          <div class="card-body" style="border-top: 1px solid rgba(0,0,0,.09)">
            <div class="row">
              <div class="col-3">
                <nuxt-link to="kirimin" class="text-center link-fluid">
                  <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="28" height="28" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><circle cx="7" cy="17" r="2" /><circle cx="17" cy="17" r="2" /><path d="M5 17h-2v-4m-1 -8h11v12m-4 0h6m4 0h2v-6h-8m0 -5h5l3 5" /><line x1="3" y1="9" x2="7" y2="9" /></svg>
                  </div>
                  <span>Kirimin</span>
                </nuxt-link>
              </div>
              <div class="col-3">
                <nuxt-link to="package" class="text-center link-fluid">
                  <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="28" height="28" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><polyline points="12 3 20 7.5 20 16.5 12 21 4 16.5 4 7.5 12 3" /><line x1="12" y1="12" x2="20" y2="7.5" /><line x1="12" y1="12" x2="12" y2="21" /><line x1="12" y1="12" x2="4" y2="7.5" /><line x1="16" y1="5.25" x2="8" y2="9.75" /></svg>
                  </div>
                  <span>Paketku</span>
                </nuxt-link>
              </div>
              <div class="col-3">
                <nuxt-link to="cekaja" class="text-center link-fluid">
                  <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="28" height="28" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M10.828 9.828a4 4 0 1 0 -5.656 0l2.828 2.829l2.828 -2.829z" /><line x1="8" y1="7" x2="8" y2="7.01" /><path d="M18.828 17.828a4 4 0 1 0 -5.656 0l2.828 2.829l2.828 -2.829z" /><line x1="16" y1="15" x2="16" y2="15.01" /></svg>
                  </div>
                  <span>CekAja</span>
                </nuxt-link>
              </div>
              <div class="col-3">
                <nuxt-link to="cekaja" class="text-center link-fluid">
                  <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M4 8v-2a2 2 0 0 1 2 -2h2" /><path d="M4 16v2a2 2 0 0 0 2 2h2" /><path d="M16 4h2a2 2 0 0 1 2 2v2" /><path d="M16 20h2a2 2 0 0 0 2 -2v-2" /><line x1="12" y1="11" x2="12" y2="11.01" /><path d="M12 18l-3.5 -5a4 4 0 1 1 7 0l-3.5 5" /></svg>
                  </div>
                  <span>Lacak</span>
                </nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
    <section class="ticket-section">
      <div class="container">
        <div class="row no-gutters mb-3">
          <div class="col">
            <strong>Ticket Support</strong>
          </div>
          <div class="col-auto">
            <nuxt-link to="ticket" style="font-size: .85rem">Lihat Semua</nuxt-link>
          </div>
        </div>
        <nuxt-link to="ticket-view" class="card text-dark text-decoration-none elevated plist mb-3" v-for="index in 3" :key="index">
          <div class="card-body">
            <div class="row">
              <div class="col">
                <h5 class="font-weight-bold m-0">SRT000001</h5>
                <span style="font-size: .85rem" class="text-muted">02 September 2021 14:32</span>
              </div>
              <div class="col-auto text-right">
                <span class="badge badge-danger px-2 py-1 font-weight-normal" style="border-radius: .25rem">Ditutup</span>
              </div>
            </div>
            <div class="mt-1">Sek ndes kapan iki dadi</div>
          </div>
        </nuxt-link>
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
    <section class="content-section">
      <div class="container">
        <div class="row no-gutters mb-3">
          <div class="col">
            <strong>Kabar baik buatmu</strong>
          </div>
          <div class="col-auto">
            <nuxt-link to="content" style="font-size: .85rem">Lihat Semua</nuxt-link>
          </div>
        </div>
        <img src="https://www.ovo.id/ovo_front_res/img/news/article-cinemaxx.jpg" class="img-fluid" alt="" style="border-radius: .35rem">
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
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
  border-radius: var(--border-radius);
  .icon {
    padding: .25rem;
    background: var(--light);
    border-radius: 100px;
    display: inline-flex;
    margin: 0 auto;
    svg {
      width: 32px;
      height: 32px;
      color: var(--dark);
    }
  }
  span {
    margin-top: .5rem;
    display: block;
    font-size: .95rem;
    font-weight: 500;
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
.plist {
  position: relative;
  &::before {
    content: "";
    position: absolute;
    left: 0;
    top: 1rem;
    bottom: 1rem;
    width: 8px;
    border-radius: 0 1rem 1rem 0;
    background: var(--danger);
  }
}

</style>
