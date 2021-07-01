<template>
  <div>
    <nav class="front-header bg-dark text-white px-2">
      <div class="container py-3">
        <img src="https://tdev.kiriminaja.com/assets/atrust/svg-logo.svg" class="mb-4" height="40px" alt="">
        <div class="balance">
          <h4><span style="font-size: 12px">Rp.</span>4.300</h4>
          <h6 class="m-0">Estimasi <span class="text-warning">4.000.000</span></h6>
        </div>
      </div>
    </nav>
    <section class="news p-2">
      <div class="container">
        <img src="https://kiriminaja.com/assets/kurir_sicepat.jpg" class="img-fluid radx" alt="">
      </div>
    </section>
    <section class="cekresi-section py-3 px-2">
      <div class="container">
        <form action="" class="track">
          <input type="text" id="track-paket" class="form-control" placeholder="Lacak paketmu">
          <label for="track-paket">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M10 2.75C14.0041 2.75 17.25 5.99594 17.25 10C17.25 11.7319 16.6427 13.3219 15.6295 14.5688L20.5303 19.4697C20.8232 19.7626 20.8232 20.2374 20.5303 20.5303C20.2641 20.7966 19.8474 20.8208 19.5538 20.6029L19.4697 20.5303L14.5688 15.6295C13.3219 16.6427 11.7319 17.25 10 17.25C5.99594 17.25 2.75 14.0041 2.75 10C2.75 5.99594 5.99594 2.75 10 2.75ZM10 4.25C6.82436 4.25 4.25 6.82436 4.25 10C4.25 13.1756 6.82436 15.75 10 15.75C13.1756 15.75 15.75 13.1756 15.75 10C15.75 6.82436 13.1756 4.25 10 4.25Z" fill="#212121"/>
            </svg>
          </label>
        </form>
      </div>
    </section>
    <section class="main-button py-2 pl-2">
      <div class="container pr-0">
        <div class="scroll-x">
          <nuxt-link to="kirimin" class="kirimin-x">
            <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
            <span>Kirimin</span>
          </nuxt-link>
          <nuxt-link to="package" class="kirimin-x">
            <img src="https://dashboard.kiriminaja.com/assets/icon/history.png" alt="">
            <span>Paketmu</span>
          </nuxt-link>
          <nuxt-link to="cekaja" class="kirimin-x">
            <img src="https://dashboard.kiriminaja.com/assets/icon/box.png" alt="">
            <span>CekAja</span>
          </nuxt-link>
          <a href="" class="kirimin-x">
            <img src="https://dashboard.kiriminaja.com/assets/icon/catalogue.png" alt="">
            <span>Katalog</span>
          </a>
          <a href="" class="kirimin-x">
            <img src="https://dashboard.kiriminaja.com/assets/icon/delivery-man.png" alt="">
            <span>Pickup</span>
          </a>
        </div>
      </div>
    </section>
    <section class="introduction p-2">
      <div class="container">
        <div class="bg-dark radx text-white">
          <div class="p-3 mt-1">
            <div class="font-weight-medium qsand">Kenali KiriminAja</div>
            <small>Tak kenal maka tak sayang...</small>
          </div>
          <div class="pl-3 py-2">
            <div class="scroll-x">
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
              <a href="">
                <img src="https://dashboard.kiriminaja.com/assets/icon/pickup.png" alt="">
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
