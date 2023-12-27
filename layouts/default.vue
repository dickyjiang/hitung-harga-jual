<template>
  <div>
    <nav class="flex justify-between gap-0 md:gap-4 text-center py-4 px-2 md:px-8">
      <div>
        <NuxtLink to="/">
          <img
            class="h-12 md:h-16 "
            src="../assets/images/hhj_logo.svg"
            alt="hitung harga jual logo"
          >
        </NuxtLink>
      </div>
      <div class="flex md:flex-row gap-2 flex-auto justify-center items-center">
        <div class="relative">
          <img
            class="h-12 md:h-16 absolute z-10 -top-3 -left-3 "
            src="../assets/images/INSTANT NOODLE 1.png"
            alt="hitung online food"
          >
          <button
            class="bg-green-600 hover:bg-green-700 text-xs md:text-sm text-white drop-shadow-xl rounded-full font-semibold py-2 md:py-3 px-5 md:px-8 mx-3 focus:outline-none focus:shadow-outline"
            type="button"
          >
            <NuxtLink to="/"> Hitung Online Food</NuxtLink>
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
            <NuxtLink to="/PageProduct"> Hitung Online Shop</NuxtLink>
          </button>
        </div>
      </div>
      <div class="hidden md:flex items-center text-gray-500 text-xs md:text-md font-semibold gap-8">
        <a href="https://www.instagram.com/hitung.harga.jual/">
          <img src="../assets/images/instagram.svg" alt="instagram">
        </a>
        <NuxtLink class="hidden" to="#">
          Berita dan Tips
        </NuxtLink>
        <NuxtLink  class="hidden" to="#">
          FAQ
        </NuxtLink>
        <NuxtLink to="/blogs">
          blog list
        </NuxtLink>
        <NuxtLink  class="hidden md:flex" to="/tentangKami">
          Tentang Kami
        </NuxtLink>
        <!-- <NuxtLink to="/kebijakanPrivasi">
          Kebijakan Privasi
        </NuxtLink> -->
        <div class=" hidden items-center text-gray-500 text-md font-semibold underline underline-offset-4 gap-4">
          <NuxtLink to="#">
            Login
          </NuxtLink>
          <NuxtLink to="#">
            Daftar
          </NuxtLink>
        </div>
      </div>
      <!-- page1
      <NuxtLink to="/page2">
        page2
      </NuxtLink>
        <NuxtLink :to="{ name: 'page2' }">About</NuxtLink>
        <NuxtLink :to="'page2'">Contact</NuxtLink> -->
      <!-- <div class=" px-3 py-1 bg-red-700 text-white font-semibold align-middle self-center ">
          TEST MODE - KALKULASI TIDAK UNTUK DIPAKAI !
        </div> -->
    </nav>
    <div>
      <slot />
    </div>

  </div>

</template>

<script>

</script>

<style>

</style>