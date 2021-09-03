<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <div class="row no-gutters">
          <div class="col">
            <h3 class="m-0 qsand">Detail Paket</h3>
          </div>
          <div class="col-auto text-center pt-1">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="28" height="28" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M17 17h2a2 2 0 0 0 2 -2v-4a2 2 0 0 0 -2 -2h-14a2 2 0 0 0 -2 2v4a2 2 0 0 0 2 2h2" /><path d="M17 9v-4a2 2 0 0 0 -2 -2h-6a2 2 0 0 0 -2 2v4" /><rect x="7" y="13" width="10" height="8" rx="2" /></svg>
          </div>
          <div class="col-auto text-center pt-1 pl-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="28" height="28" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><circle cx="6" cy="12" r="3" /><circle cx="18" cy="6" r="3" /><circle cx="18" cy="18" r="3" /><line x1="8.7" y1="10.7" x2="15.3" y2="7.3" /><line x1="8.7" y1="13.3" x2="15.3" y2="16.7" /></svg>
          </div>
        </div>
      </div>
    </nav>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-6">No Invoice</div>
          <div class="col-6 font-weight-medium text-right">OID-00000001</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6">No Resi</div>
          <div class="col-6 font-weight-medium text-right">SAP-20023000</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6">Kurir</div>
          <div class="col-6 font-weight-medium text-right">AnterAja - Reguler</div>
          <div class="col-12 mt-2"></div>
        </div>
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
    <section class="package-detail">
      <div class="container">
        <h5 class="font-weight-bold">Info Pengiriman</h5>
        <div class="card border-0" style="background: rgba(255,0,0,.15)">
          <div class="card-body">
            <span style="font-size: .85rem">Status</span>
            <h6 class="font-weight-bold text-danger">Dibatalkan oleh Yanuar Aditia</h6>
            <hr>
            <span style="font-size: .85rem">Tanggal Dibuat</span>
            <h6 class="font-weight-normal">16 Juli 2021, 10:41 WIB</h6>
          </div>
        </div>
        <div class="sender-name mt-3" style="padding-left: 4rem">
          <span style="font-size: .75rem">Lokasi Pengirim</span>
          <h5 style="font-size: 1.15rem">Yanuar Aditia</h5>
          <p class="text-muted" style="font-size: .85rem">Jl. Alpokat No.45F Perumnas Condong Catur, Kec. Depok, Kabupaten Sleman, Daerah Istimewa Yogyakarta</p>
        </div>
        <div class="receiver-name" style="padding-left: 4rem">
          <span style="font-size: .75rem">Tujuan Pengantaran</span>
          <h5 style="font-size: 1.15rem">Yanuar Aditia</h5>
          <p class="text-muted" style="font-size: .85rem">Jl. Alpokat No.45F Perumnas Condong Catur, Kec. Depok, Kabupaten Sleman, Daerah Istimewa Yogyakarta</p>
        </div>
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
    <section class="price-detail">
      <div class="container">
        <h5 class="font-weight-bold">Detail Paket</h5>
        <div class="row">
          <div class="col-6">Metode Pembayaran</div>
          <div class="col-6 font-weight-medium text-right">COD</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6">Nilai Barang</div>
          <div class="col-6 font-weight-medium text-right">Rp. 100</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6">Biaya Kirim</div>
          <div class="col-6 font-weight-medium text-right">Rp. 7.000</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6">COD Fee</div>
          <div class="col-6 font-weight-medium text-right">Rp. 300</div>
          <div class="col-12">
            <hr>
          </div>
          <div class="col-6 font-weight-medium">Saldo Cair</div>
          <div class="col-6 font-weight-medium text-right">Rp. 100</div>
          <div class="col-12 mt-2"></div>
          <div class="col-6 font-weight-medium">Tagihan Penerima</div>
          <div class="col-6 font-weight-medium text-right">Rp. 7.400</div>
        </div>
      </div>
    </section>
    <div style="height: 10px; background: #f1f1f1" class="my-4"></div>
    <section>
      <div class="container">
        <div class="row no-gutters">
          <div class="col-auto">
            <button class="btn btn-primary">
              <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M17 17h2a2 2 0 0 0 2 -2v-4a2 2 0 0 0 -2 -2h-14a2 2 0 0 0 -2 2v4a2 2 0 0 0 2 2h2" /><path d="M17 9v-4a2 2 0 0 0 -2 -2h-6a2 2 0 0 0 -2 2v4" /><rect x="7" y="13" width="10" height="8" rx="2" /></svg>
              Label
            </button>
          </div>
          <div class="col pl-2">
            <button class="btn btn-outline-primary btn-block">Lacak Paket</button>
          </div>
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
