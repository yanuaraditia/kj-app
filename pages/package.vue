<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <h3 class="m-0 qsand">Paketku</h3>
      </div>
    </nav>
    <section class="filter-data">
      <div class="container">
        <nuxt-link to="package-list" class="text-decoration-none mb-2 d-block">
          <div class="card card-body border-0 text-white" style="background: #0069c0">
            <h4>Belum Dipickup</h4>
            <div class="text-right">
              <h3>24</h3>
            </div>
          </div>
        </nuxt-link>
        <nuxt-link to="package-list" class="text-decoration-none mb-2 d-block">
          <div class="card card-body border-0 text-white" style="background: #5c6bc0">
            <h4>Dalam Pengiriman</h4>
            <div class="text-right">
              <h3>24</h3>
            </div>
          </div>
        </nuxt-link>
        <nuxt-link to="package-list" class="text-decoration-none mb-2 d-block">
          <div class="card card-body border-0 text-white" style="background: #087f23">
            <h4>Sampai Tujuan</h4>
            <div class="text-right">
              <h3>24</h3>
            </div>
          </div>
        </nuxt-link>
        <nuxt-link to="package-list" class="text-decoration-none mb-2 d-block">
          <div class="card card-body border-0 text-white" style="background: #ba000d">
            <h4>Return</h4>
            <div class="text-right">
              <h3>24</h3>
            </div>
          </div>
        </nuxt-link>
        <nuxt-link to="package-list" class="text-decoration-none d-block">
          <div class="card card-body border-0 text-white" style="background: #0069c0">
            <h4>Dibatalkan</h4>
            <div class="text-right">
              <h3>24</h3>
            </div>
          </div>
        </nuxt-link>
      </div>
    </section>
  </div>
</template>
