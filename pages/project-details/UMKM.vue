<template>
  <!-- HERO -->
  <section class="bg-gradient-to-br from-blue-600 to-indigo-700 text-white">
    <div class="max-w-6xl mx-auto px-6 py-28 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm
               bg-white/20 rounded-full"
      >
        Project Details
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Aplikasi UMKM
      </h1>

      <p class="text-blue-100 max-w-2xl mx-auto text-lg">
        Solusi digital untuk membantu UMKM mengelola penjualan,
        transaksi, dan laporan bisnis secara lebih mudah & efisien.
      </p>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-6xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16">
    <!-- LEFT -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">
        Gambaran Project
      </h2>

      <p class="text-gray-600 mb-6">
        Aplikasi UMKM ini dirancang khusus untuk pelaku usaha kecil
        dan menengah agar dapat melakukan pencatatan penjualan,
        pengelolaan produk, serta laporan keuangan dengan mudah
        tanpa sistem yang rumit.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Pencatatan transaksi harian</li>
        <li>Manajemen produk & harga</li>
        <li>Laporan penjualan otomatis</li>
        <li>Mudah digunakan (user friendly)</li>
        <li>Cocok untuk berbagai jenis usaha</li>
      </ul>
    </div>

    <!-- RIGHT -->
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <h3 class="text-xl font-semibold mb-4">
        Fitur Utama
      </h3>

      <ul class="space-y-4 text-gray-600 mb-6">
        <li>• Dashboard penjualan</li>
        <li>• Manajemen produk & kategori</li>
        <li>• Pencatatan transaksi kasir</li>
        <li>• Laporan harian & bulanan</li>
        <li>• Export laporan</li>
      </ul>

      <div class="flex flex-col gap-4">
        <NuxtLink
          to="/portfolio"
          class="inline-block text-center px-6 py-3 rounded-xl
                 border text-gray-700 hover:bg-gray-100 transition"
        >
          ← Kembali ke Portfolio
        </NuxtLink>

        <NuxtLink
          to="/contact"
          class="inline-block text-center px-6 py-3 rounded-xl
                 bg-blue-600 text-white hover:bg-blue-700 transition font-semibold"
        >
          Konsultasi Aplikasi UMKM
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- TECH STACK -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-12">
        Teknologi yang Digunakan
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Frontend</h4>
          <p class="text-sm text-gray-600">
            Vue / Nuxt + Tailwind CSS
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Backend</h4>
          <p class="text-sm text-gray-600">
            API / Laravel / Firebase
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Database</h4>
          <p class="text-sm text-gray-600">
            MySQL / Cloud Database
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- BENEFITS -->
  <section>
    <div class="max-w-6xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-12">
        Manfaat untuk UMKM
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Lebih Rapi</h4>
          <p class="text-sm text-gray-600">
            Data penjualan tersimpan otomatis
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Hemat Waktu</h4>
          <p class="text-sm text-gray-600">
            Tidak perlu pencatatan manual
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Mudah Digunakan</h4>
          <p class="text-sm text-gray-600">
            Cocok untuk pemula sekalipun
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- STATUS -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-20 text-center">
      <div class="text-4xl mb-4">🏪</div>

      <h2 class="text-2xl font-semibold mb-4">
        Status Project
      </h2>

      <p class="text-gray-600 max-w-xl mx-auto">
        Aplikasi UMKM ini telah digunakan sebagai sistem
        pencatatan usaha dan dapat dikembangkan sesuai
        kebutuhan masing-masing pelaku UMKM.
      </p>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-blue-600 text-white">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Ingin Aplikasi untuk UMKM Anda?
      </h2>

      <p class="text-blue-100 max-w-xl mx-auto mb-8">
        Kami siap membantu digitalisasi usaha Anda
        dengan sistem yang sederhana & efektif.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-blue-600 px-8 py-4
               rounded-xl font-semibold hover:bg-blue-100 transition"
      >
        Konsultasi Gratis
      </NuxtLink>
    </div>
  </section>
</template>
