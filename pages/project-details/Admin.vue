<template>
  <!-- HERO -->
  <section class="bg-gradient-to-br from-gray-900 to-black text-white">
    <div class="max-w-5xl mx-auto px-6 py-28 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm
               text-gray-300 border border-white/20 rounded-full"
      >
        Project Details
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Admin Dashboard
      </h1>

      <p class="text-gray-300 max-w-xl mx-auto text-lg">
        Halaman detail project ini sedang dalam tahap pengembangan.
        Kami sedang menyiapkan dokumentasi dan preview terbaik untuk Anda.
      </p>
    </div>
  </section>

  <!-- CONTENT -->
  <section class="max-w-4xl mx-auto px-6 py-24 text-center">
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <div class="text-5xl mb-6">🚧</div>

      <h2 class="text-2xl font-semibold mb-4">
        Sedang Dalam Pengembangan
      </h2>

      <p class="text-gray-600 mb-6">
        Project Admin Dashboard ini mencakup sistem manajemen data,
        monitoring, dan kontrol operasional.  
        Detail lengkap akan segera tersedia.
      </p>

      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <NuxtLink
          to="/portfolio"
          class="px-6 py-3 rounded-xl border
                 text-gray-700 hover:bg-gray-100 transition"
        >
          ← Kembali ke Portfolio
        </NuxtLink>

        <NuxtLink
          to="/contact"
          class="px-6 py-3 rounded-xl bg-black text-white
                 hover:bg-gray-800 transition font-semibold"
        >
          Konsultasi Project Serupa
        </NuxtLink>
      </div>
    </div>
  </section>
</template>
