<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <h3 class="m-0 qsand">Detail Paket</h3>
      </div>
    </nav>
    <section class="package-detail">
      <div class="container">
        <div class="card border-0" style="border-radius: .25rem; background: rgba(255,0,0,.15)">
          <div class="card-body">
            <span style="font-size: .85rem">Status Pengiriman</span>
            <h6 class="font-weight-bold text-danger">Dibatalkan oleh Yanuar Aditia</h6>
            <hr>
            <span style="font-size: .85rem">Alasan Batal</span>
            <h6 class="font-weight-normal">Mboh ra roh</h6>
          </div>
        </div>
        <div class="sender-name mt-3" style="padding-left: 4rem">
          <span style="font-size: .75rem">Lokasi Pengirim</span>
          <h5>Yanuar Aditia</h5>
          <p class="text-muted">Jl. Alpokat No.45F Perumnas Condong Catur, Kec. Depok, Kabupaten Sleman, Daerah Istimewa Yogyakarta</p>
        </div>
        <div class="receiver-name" style="padding-left: 4rem">
          <span style="font-size: .75rem">Tujuan Pengantaran</span>
          <h5>Yanuar Aditia</h5>
          <p class="text-muted">Jl. Alpokat No.45F Perumnas Condong Catur, Kec. Depok, Kabupaten Sleman, Daerah Istimewa Yogyakarta</p>
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped lang="scss">
.sender-name, .receiver-name {
  position: relative;
  &::before {
    content: "";
    width: 28px;
    height: 28px;
    border: 7px solid var(--primary);
    position: absolute;
    left: 1rem;
    top: .5rem;
    border-radius: 100%;
  }
}
.sender-name {
  &::after {
    top: 3rem;
    left: 1.75rem;
    content: "";
    width: 3px;
    height: calc(100% - 2rem);
    border-left: 3px dashed #eee;
    position: absolute;
  }
}
.receiver-name {
  &::before {
    border-color: var(--warning);
  }
}
</style>
