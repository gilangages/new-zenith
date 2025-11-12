<script setup></script>
<template>
  <div class="min-h-screen bg-white">
    <!-- MAIN CONTENT -->
    <main
      class="px-4 sm:px-8 md:px-12 py-8 md:py-10 grid grid-cols-1 md:grid-cols-3 gap-8 md:gap-10"
    >
      <!-- LEFT SECTION -->
      <div class="md:col-span-2 border rounded-lg p-6 md:p-8 shadow-sm">
        <h2 class="text-lg font-semibold mb-4">Scan QR Code</h2>
        <div
          class="w-full sm:w-64 h-64 mx-auto bg-gray-100 flex items-center justify-center rounded-lg border mb-4"
        >
          <span class="text-gray-400">[QR Code]</span>
        </div>

        <div class="bg-blue-50 border border-blue-200 rounded-lg p-4">
          <h3 class="font-semibold mb-2 text-blue-600">Cara Pembayaran:</h3>
          <ul class="list-decimal list-inside text-gray-700 text-sm space-y-1">
            <li>Buka aplikasi e-wallet Anda (Dana, OVO, Gopay, dll)</li>
            <li>Pilih menu “Scan QR”</li>
            <li>Arahkan kamera ke kode QR di atas</li>
            <li>Pastikan nominal sudah sesuai sebelum konfirmasi</li>
          </ul>
        </div>

        <!-- Tombol di kanan -->
        <div class="flex justify-end">
          <button
            class="mt-6 bg-pink-500 text-white px-6 py-2 rounded-lg hover:bg-pink-600 transition w-full sm:w-auto"
          >
            Konfirmasi Pembayaran
          </button>
        </div>
      </div>

      <!-- RIGHT SECTION -->
      <div class="border rounded-lg p-6 shadow-sm">
        <h3 class="text-lg font-semibold mb-4">Detail Transaksi</h3>
        <div class="text-sm space-y-2 text-gray-700">
          <p><strong>ID Pembayaran:</strong> 1181706861499970578TOP</p>
          <p><strong>Metode:</strong> QRIS</p>
          <p><strong>Alamat Pengiriman:</strong> Jalan Adisumarmo No. 61</p>
          <p><strong>Atas Nama:</strong> Bagas Ardian</p>

          <hr class="my-3" />
          <p><strong>Sub Total:</strong> Rp 14.590.000</p>
          <p class="text-pink-600 font-semibold">
            Total Pembayaran: Rp 14.593.000
          </p>

          <hr class="my-3" />
          <h4 class="font-semibold mb-2">Pesanan Anda:</h4>
          <div class="border rounded-lg p-3 bg-gray-50">
            <p class="text-sm font-medium">
              Samsung Galaxy S23 Ultra 512GB (Green)
            </p>
            <p class="text-gray-500 text-sm">Qty: 1</p>
            <p class="text-gray-700 font-semibold mt-2">Rp 14.593.000</p>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<style scoped>
/* gunakan FontAwesome jika mau icon keranjang tampil */
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css";
</style>
