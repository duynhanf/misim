<template>
  <div class="app">
    <section class="border-b border-black">
      <div class="flex justify-between py-4 w-[1280px] mx-auto">
        <a class="" href="/">
          <div class="">
            <img src="https://www.mioto.vn/static/media/logo-full.ea382559.png" class="w-25" alt="Mioto">
          </div>
        </a>
        <div class="">
          <ul class="flex">
            <li class="list-none pl-5">
              <Link to="/about">
                Về MiSim
              </Link>
            </li>
            <li class="list-none pl-5">
              Đăng ký sim
            </li>
            <li class="list-none pl-5">
              Blog
            </li>
            <li class="list-none pl-5">
              Đăng ký
            </li>
            <li class="list-none pl-5">
              Đăng nhập
            </li>
          </ul>
          <!-- <a class="dropdown-profile">
            <div class="wrap-svg tab-menu">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 6H19" stroke="black" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" /><path d="M5 18H19" stroke="black" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" /><path d="M5 12H19" stroke="black" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" /></svg>
            </div>
          </a> -->
          <!-- <div class="menu-mobile open move-left">
            <div class="header-menu">
              <div class="close-menu">
                ×
              </div>
            </div>
            <div class="m-container">
              <div class="menu-list">
                <a class="menu-list__item">Đăng nhập</a>
                <div class="line-page">
                  <a class="menu-list__item">Đăng ký</a>
                </div>
                <div class="menu-list">
                  <a class="menu-list__item" href="/aboutus">Về Mioto</a>
                  <div class="line-page">
                    <a class="menu-list__item" href="/owner/register">Trở thành chủ sim</a>
                    <a class="menu-list__item" href="/blogs">Blog</a>
                  </div>
                </div>
              </div>
            </div>
          </div> -->
        </div>
      </div>
    </section>
    <NuxtPage />
  </div>
</template>

<style>
.app {
  font-family: Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
}
</style>
