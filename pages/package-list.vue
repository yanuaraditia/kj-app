<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <h3 class="m-0 qsand">Belum Dipickup</h3>
      </div>
    </nav>
    <section class="package-list">
      <div class="container">
        <nuxt-link to="package-view" class="card text-dark text-decoration-none elevated plist mb-3" v-for="index in 10" :key="index">
          <div class="card-body">
            <div class="row">
              <div class="col">
                <span style="font-size: .85rem" class="text-muted">02 September 2021 14:32</span>
                <h6 class="my-1 font-weight-bold">Ilham Test</h6>
                <span class="badge badge-light px-2 py-1" style="border-radius: .25rem">COD</span>
                <span style="font-size: .85rem">OID-KIRIMINAJA</span>
              </div>
              <div class="col-auto text-right">
                <div>
                  <img src="https://kiriminaja.com/assets/logistics/sicepat.png" width="80px" alt="">
                </div>
                <div>
                  <span>1420233020900</span>
                </div>
              </div>
            </div>
          </div>
        </nuxt-link>
      </div>
    </section>
  </div>
</template>
<style scoped lang="scss">
.plist {
  position: relative;
  &::before {
    content: "";
    position: absolute;
    left: 0;
    top: 1rem;
    bottom: 1rem;
    width: 4px;
    border-radius: 0 1rem 1rem 0;
    background: var(--success);
  }
}
</style>
