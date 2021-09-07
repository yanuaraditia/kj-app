<template>
  <div>
    <nav class="bottom-nav">
      <div class="container mx-40vw">
        <div class="row text-center no-gutters">
          <div class="col">
            <nuxt-link to="/">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M10.5495 2.53189C11.3874 1.82531 12.6126 1.82531 13.4505 2.5319L20.2005 8.224C20.7074 8.65152 21 9.2809 21 9.94406V19.7468C21 20.7133 20.2165 21.4968 19.25 21.4968H15.75C14.7835 21.4968 14 20.7133 14 19.7468V14.2468C14 14.1088 13.8881 13.9968 13.75 13.9968H10.25C10.1119 13.9968 9.99999 14.1088 9.99999 14.2468V19.7468C9.99999 20.7133 9.2165 21.4968 8.25 21.4968H4.75C3.7835 21.4968 3 20.7133 3 19.7468V9.94406C3 9.2809 3.29255 8.65152 3.79952 8.224L10.5495 2.53189ZM12.4835 3.6786C12.2042 3.44307 11.7958 3.44307 11.5165 3.6786L4.76651 9.37071C4.59752 9.51321 4.5 9.72301 4.5 9.94406V19.7468C4.5 19.8849 4.61193 19.9968 4.75 19.9968H8.25C8.38807 19.9968 8.49999 19.8849 8.49999 19.7468V14.2468C8.49999 13.2803 9.2835 12.4968 10.25 12.4968H13.75C14.7165 12.4968 15.5 13.2803 15.5 14.2468V19.7468C15.5 19.8849 15.6119 19.9968 15.75 19.9968H19.25C19.3881 19.9968 19.5 19.8849 19.5 19.7468V9.94406C19.5 9.72301 19.4025 9.51321 19.2335 9.37071L12.4835 3.6786Z" fill="currentColor"/>
              </svg>
              <span>Home</span>
            </nuxt-link>
          </div>
          <div class="col">
            <nuxt-link to="/package">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M7 7V5C7 3.34315 8.34315 2 10 2C10.7684 2 11.4692 2.28886 12 2.7639C12.5308 2.28885 13.2317 2 14 2C15.6569 2 17 3.34315 17 5V7H18.5C19.3284 7 20 7.67157 20 8.5V18.505C20 20.4352 18.4352 22 16.505 22H8C5.79086 22 4 20.2091 4 18V8.5C4 7.67157 4.67157 7 5.5 7H7ZM13.635 20.5C13.241 19.9343 13.01 19.2466 13.01 18.505V8.5H5.5V18C5.5 19.3807 6.61929 20.5 8 20.5H13.635ZM11.5 7V5C11.5 4.17157 10.8284 3.5 10 3.5C9.17157 3.5 8.5 4.17157 8.5 5V7H11.5ZM13 7H15.5V5C15.5 4.17157 14.8284 3.5 14 3.5C13.535 3.5 13.1195 3.71156 12.8444 4.04368C12.9453 4.34403 13 4.66563 13 5V7ZM14.51 18.505C14.51 19.6068 15.4032 20.5 16.505 20.5C17.6068 20.5 18.5 19.6068 18.5 18.505V8.5H14.51V18.505Z" fill="currentColor"/>
              </svg>
              <span>Paket</span>
            </nuxt-link>
          </div>
          <div class="col px-0">
            <nuxt-link to="/kirimin" class="super-link">
              <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><line x1="12" y1="5" x2="12" y2="19" /><line x1="5" y1="12" x2="19" y2="12" /></svg>
            </nuxt-link>
          </div>
          <div class="col">
            <nuxt-link to="/account">
              <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M3 20l1.3 -3.9a9 8 0 1 1 3.4 2.9l-4.7 1" /><line x1="12" y1="12" x2="12" y2="12.01" /><line x1="8" y1="12" x2="8" y2="12.01" /><line x1="16" y1="12" x2="16" y2="12.01" /></svg>
              <span>Support</span>
            </nuxt-link>
          </div>
          <div class="col">
            <nuxt-link to="/account">
              <img width="24px" height="24px" class="fullrad" src="https://kiriminaja.com/storage/Users/Juni2021/985_29_02-50-19.jpg" alt="">
              <span>Akun</span>
            </nuxt-link>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
