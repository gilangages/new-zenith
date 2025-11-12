<script setup>
// Navbar User — sudah responsive & mobile-friendly
</script>

<template>
  <nav class="w-full bg-white shadow-sm py-3 md:py-4">
    <div
      class="max-w-6xl mx-auto flex items-center justify-between flex-wrap gap-3 px-4 md:px-6"
    >
      <!-- LOGO -->
      <div class="flex items-center flex-shrink-0">
        <img src="../assets/logo.png" alt="Zenith Logo" class="h-9 w-auto" />
      </div>

      <!-- SEARCH BAR -->
      <div class="flex-1 flex justify-center md:justify-center min-w-0">
        <div
          class="flex items-center border rounded-full overflow-hidden bg-pink-50 w-full max-w-md"
        >
          <input
            type="text"
            placeholder="Cari produk"
            class="flex-1 bg-transparent px-3 py-2 text-sm text-gray-700 focus:outline-none"
          />
          <button
            class="bg-pink-500 hover:bg-pink-600 text-white px-3 py-2 text-sm"
          >
            <i class="fa fa-search"></i>
          </button>
        </div>
      </div>

      <!-- CART & PROFILE -->
      <div class="flex items-center space-x-4 flex-shrink-0">
        <!-- Cart -->
        <button>
          <i class="fa fa-shopping-cart text-pink-500 text-lg md:text-xl"></i>
        </button>

        <!-- Profile -->
        <div class="flex items-center space-x-2 ml-3">
          <img
            src="../assets/ip.png"
            class="w-12 h-12 rounded-full"
            alt="profile"
          />
          <span class="font-medium text-gray-700 text-sm hidden sm:inline">
            raditya.ba
          </span>
        </div>
      </div>
    </div>
  </nav>
  <div class="flex justify-end my-3">
    <button
      class="flex items-center justify-center space-x-2 px-4 py-2 text-white text-sm font-semibold rounded-lg w-40 md:w-40"
      style="background: linear-gradient(to right, #e91e63, #3f51b5)"
    >
      <i class="fa fa-desktop"></i>
      <span>DESKTOP LAB</span>
    </button>
  </div>
</template>

<style scoped>
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css";
</style>
