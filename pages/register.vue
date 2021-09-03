<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <img src="https://kiriminaja.com/assets/atrust/svg-logo-primary.svg" class="mb-4" height="40px" alt="">
        <h3 class="mb-3 mt-5 qsand">Gabung ke KiriminAja</h3>
        <form action="">
          <div class="form-group">
            <label for="name" class="font-weight-medium required">Nama Lengkap</label>
            <input type="text" name="email" id="name" placeholder="Contoh: Fariz" class="form-control">
          </div>
          <div class="form-group">
            <label for="email" class="font-weight-medium required">E-mail</label>
            <input type="email" name="email" id="email" placeholder="saya@email.com" class="form-control">
          </div>
          <div class="form-group">
            <label for="phone" class="font-weight-medium required">Nomor Telepon / WA</label>
            <input type="tel" name="email" id="phone" placeholder="08xxxxxx" class="form-control">
          </div>
          <div class="form-group">
            <label for="password" class="font-weight-medium required">Password</label>
            <input type="password" name="password" id="password" placeholder="Kata sandi anda" class="form-control">
          </div>
          <div class="form-group">
            <label for="password-confirmation" class="font-weight-medium required">Konfirmasi Password</label>
            <input type="password" name="password" id="password-confirmation" placeholder="Kata sandi anda" class="form-control">
          </div>
          <div class="form-group">
            <label for="referal" class="font-weight-medium">Kode Referal (Jika ada)</label>
            <input type="text" name="email" id="referal" placeholder="Nomor referal" class="form-control">
          </div>
          <button class="btn btn-primary btn-block">Daftar</button>
          <button class="btn btn-info btn-block mt-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M17.788 5.108a9 9 0 1 0 3.212 6.892h-8" /></svg>
            <span class="px-3 d-inline-flex">Gabung dengan Google</span>
          </button>
          <div class="mt-3 text-center">
            Sudah punya akun? <nuxt-link to="login">Masuk sekarang</nuxt-link>
          </div>
        </form>
      </div>
    </nav>
  </div>
</template>
<style lang="scss" scoped>
.or {
  position: relative;
  &::before {
    top: calc(50% - 1px);
    height: 2px;
    width: 100%;
    background: #eee;
    position: absolute;
    left: 0;
    right: 0;
    content: "";
  }
  span {
    position: relative;
    background: #fff;
  }
}
.bottom-nav {
  display: none!important;
}
</style>
