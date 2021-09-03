<template>
  <div>
    <nav class="page-header py-3">
      <div class="container">
        <img src="https://kiriminaja.com/assets/atrust/svg-logo-primary.svg" height="40px" alt="">
        <h3 class="my-3 qsand">Masuk ke KiriminAja</h3>
        <button class="btn btn-info font-weight-normal p-2" style="border-radius: .35rem">
          <span class="bg-white p-1 d-inline-flex" style="border-radius: .35rem">
            <img src="~/assets/img.png" width="24px" height="24px" alt="">
          </span>
          <span class="px-3 d-inline-flex" style="transform: translateY(-5px)">
          Login Dengan Google
          </span>
        </button>
        <div class="or my-4 text-center">
          <span class="px-2">Atau</span>
        </div>
        <form action="">
          <div class="form-group">
            <label for="email" class="font-weight-medium">E-mail</label>
            <input type="text" name="email" id="email" placeholder="saya@email.com" class="form-control">
          </div>
          <div class="form-group">
            <div class="row">
              <div class="col">
                <label for="password" class="font-weight-medium">Password</label>
              </div>
              <div class="col text-right">
                <a href="#">Lupa password?</a>
              </div>
            </div>
            <input type="password" name="password" id="password" placeholder="Kata sandi anda" class="form-control">
          </div>
          <button class="btn btn-primary btn-block">Masuk</button>
          <div class="mt-3 text-center">
            Belum punya akun? <a href="#">Daftar sekarang</a>
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
