<template>
  <div>
    <nav class="flex justify-between gap-0 md:gap-4 text-center py-4 px-2 md:px-8">
      <div>
        <nuxt-link to="/">
          <img
            class="h-12 md:h-16 "
            src="../assets/images/hhj_logo.svg"
            alt="hitung harga jual logo"
          >
        </nuxt-link>
      </div>
      <div class="flex md:flex-row gap-2 flex-auto justify-center items-center">
        <div class="relative">
          <img
            class="h-12 md:h-16 absolute z-10 -top-3 -left-3 "
            src="../assets/images/INSTANT NOODLE 1.png"
            alt="hitung online food"
          >
          <button
            class="bg-greenbrand hover:bg-green-700 text-xs md:text-sm text-white drop-shadow-xl rounded-full font-semibold py-2 md:py-3 px-5 md:px-8 mx-3 focus:outline-none focus:shadow-outline"
            type="button"
          >
            <nuxt-link to="/"> Hitung Online Food</nuxt-link>
          </button>
        </div>
        <div class="relative">
          <img
            class="h-12 md:h-16 absolute z-10 -left-3 -top-3 "
            src="../assets/images/olshop_orange-icon.png"
            alt="hitung online food"
          >
          <button
            class="bg-fuchsia-500 hover:bg-fuchsia-700 text-xs md:text-sm text-white drop-shadow-xl rounded-full font-semibold py-2 md:py-3 px-5 md:px-8 mx-3 focus:outline-none focus:shadow-outline"
            type="button"
          >
            <nuxt-link to="/PageProduct"> Hitung Online Shop</nuxt-link>
          </button>
        </div>
      </div>
      <div class="hidden md:flex items-center text-gray-500 text-xs md:text-md font-semibold gap-8">
        <a href="https://www.instagram.com/hitung.harga.jual/">
          <img src="../assets/images/instagram.svg" alt="instagram">
        </a>
        <nuxt-link class="hidden" to="#">
          Berita dan Tips
        </nuxt-link>
        <nuxt-link  class="hidden" to="#">
          FAQ
        </nuxt-link>
        <nuxt-link to="/listBlog">
          blog list
        </nuxt-link>
        <nuxt-link  class="hidden md:flex" to="/tentangKami">
          Tentang Kami
        </nuxt-link>
        <!-- <nuxt-link to="/kebijakanPrivasi">
          Kebijakan Privasi
        </nuxt-link> -->
        <div class=" hidden items-center text-gray-500 text-md font-semibold underline underline-offset-4 gap-4">
          <nuxt-link to="#">
            Login
          </nuxt-link>
          <nuxt-link to="#">
            Daftar
          </nuxt-link>
        </div>
      </div>
      <!-- page1
      <NuxtLink to="/page2">
        page2
      </NuxtLink>
        <nuxt-link :to="{ name: 'page2' }">About</nuxt-link>
        <nuxt-link :to="'page2'">Contact</nuxt-link> -->
      <!-- <div class=" px-3 py-1 bg-red-700 text-white font-semibold align-middle self-center ">
          TEST MODE - KALKULASI TIDAK UNTUK DIPAKAI !
        </div> -->
    </nav>
    <!-- <slot /> -->

  </div>

</template>

<script>

</script>

<style>

</style>