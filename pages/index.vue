<template>
  <div class="flex flex-col min-h-screen w-full">
    <div class="w-full flex sticky bg-white top-0 h-16 shadow">
      <div
        class="flex w-full max-w-2xl mx-auto items-center min-w-md justify-around"
      >
        <Logo></Logo>
        <nuxt-link :to="'/'" class="link pt-1">Tentang</nuxt-link>
        <nuxt-link :to="'/'" class="link pt-1">Layanan</nuxt-link>
        <nuxt-link :to="'/'" class="link pt-1">Lokasi</nuxt-link>
        <button
          class="link text-white bg-black py-2 px-4 appearance-none hover:bg-white hover:text-black focus:outline-none"
        >
          <div class="pt-1">Cek Status</div>
        </button>
      </div>
    </div>
    <div class="h-screen w-full bg-home">
      <div class="flex flex-col h-full">
        <div
          class="flex flex-col mt-auto mx-auto justify-center text-white main-title"
        >
          <div class="mx-auto" style="letter-spacing: 0.08em;">STAR</div>
          <div>WASH</div>
        </div>
        <div class="flex flex-col mb-auto top-0 mx-auto text-white sub-title">
          Cleaning Your Shoes Since 2017
        </div>
      </div>
    </div>
    <div class="h-screen w-full bg-2">
      <div class="flex flex-col h-full">
        <div class="flex m-auto justify-center text-white max-w-xl">
          <div class="flex flex-col w-3/4 mr-2">
            <div class="mr-auto sub-title" style="letter-spacing: 0.08em;">
              Tentang Kami
            </div>
            <div class="text-sm leading-loose font-medium">
              STARWASH SHOE, shoe laundry yg berdiri sejak tahun 2017 yang pada
              tahun ini menginjak umur ke 2 nya dan telah menangani kurang lebih
              5000 sepatu kotor di daerah malang dan Surabaya, starwash
              merupakan shoe laundry yang menawarkan treatment sepatu dengan
              harga ekonomis dengan kualitas yang bias dibilang top, starwash
              juga melayani delivery order untuk sobat-sobat pemalah daerah
              malang kota dan Surabaya. Treatment lain yang dapat di jumpai di
              starwash selain cuci deep clean ada juga treatment one day service
              atau biasa khalayak menyebutnya ODS yaitu treatment pencucian
              sepatu yang hanya membutuhkan waktu pengerjaan selama 1 hari,
              selain itu ada juga treatment untuk recolour, repaint, unyellowing
              dan lain-lainnya.
            </div>
          </div>
          <div class="flex flex-col justify-around">
            <img style="width: 96px" src="../static/img/about/1.jpg" />
            <img style="width: 96px" src="../static/img/about/2.jpg" />
            <img style="width: 96px" src="../static/img/about/3.jpg" />
          </div>
        </div>
      </div>
    </div>
    <div class="bg-white h-64 flex flex-col mx-auto">
      <div
        class="flex flex-col justify-center items-center text-xs mt-auto mb-6"
      >
        <p>
          COUNTRY : INDONESIA
        </p>
        <p>
          © COPYRIGHT 2019 STAR WASH SHOE, INC
        </p>
        <p>
          ALL RIGHTS RESERVED.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: { Logo }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.bg-home {
  background-image: url('../static/img/bg-home.jpg');
  background-size: cover;
  background-position: center;
}
.bg-2 {
  background-image: url('../static/img/bg-2.jpg');
  background-size: cover;
  background-position: center;
}
</style>
