<template>
  <!-- HERO -->
  <section class="bg-gradient-to-br from-gray-900 to-black text-white">
    <div class="max-w-6xl mx-auto px-6 py-28 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm
               text-gray-300 border border-white/20 rounded-full"
      >
        Project Details
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Book App / Booking System
      </h1>

      <p class="text-gray-300 max-w-2xl mx-auto text-lg">
        Aplikasi booking berbasis web untuk mempermudah
        pelanggan melakukan reservasi layanan secara online,
        cepat, dan terorganisir.
      </p>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-6xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16">
    <!-- LEFT -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">
        Tentang Project
      </h2>

      <p class="text-gray-600 mb-6">
        Book App dirancang untuk bisnis berbasis layanan seperti
        klinik, salon, bengkel, konsultasi, atau jasa profesional
        agar proses pemesanan tidak lagi manual.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Booking layanan secara online</li>
        <li>Manajemen jadwal & ketersediaan</li>
        <li>Notifikasi otomatis (email / WhatsApp)</li>
        <li>Dashboard admin & laporan</li>
        <li>Manajemen pelanggan</li>
      </ul>
    </div>

    <!-- RIGHT -->
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <h3 class="text-xl font-semibold mb-4">
        Teknologi & Fitur
      </h3>

      <ul class="space-y-4 text-gray-600 mb-6">
        <li>• Frontend modern & responsif</li>
        <li>• Sistem login & role</li>
        <li>• Kalender & time-slot booking</li>
        <li>• Database terintegrasi</li>
        <li>• Siap dikembangkan ke mobile app</li>
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
                 bg-black text-white hover:bg-gray-800 transition font-semibold"
        >
          Konsultasi Booking App
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- STATUS -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <div class="text-4xl mb-4">🚧</div>

      <h2 class="text-2xl font-semibold mb-4">
        Status Pengembangan
      </h2>

      <p class="text-gray-600 max-w-xl mx-auto">
        Project Book App masih dalam tahap pengembangan.
        Detail fitur lanjutan, demo, dan studi kasus akan
        ditampilkan setelah versi stabil dirilis.
      </p>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Ingin Sistem Booking untuk Bisnis Anda?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Kami siap membangun sistem booking yang efisien,
        aman, dan sesuai alur bisnis Anda.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-8 py-4
               rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Diskusi Sekarang
      </NuxtLink>
    </div>
  </section>
</template>
