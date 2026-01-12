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
        Sistem Akademik Sekolah
      </h1>

      <p class="text-gray-300 max-w-2xl mx-auto text-lg">
        Sistem akademik berbasis web untuk membantu sekolah
        mengelola data siswa, guru, nilai, dan laporan akademik
        secara terpusat dan efisien.
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
        Sistem Akademik ini dirancang untuk sekolah dan institusi pendidikan
        agar proses administrasi akademik menjadi lebih cepat,
        akurat, dan terdigitalisasi.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Manajemen data siswa & guru</li>
        <li>Pengelolaan nilai & raport</li>
        <li>Jadwal pelajaran & kelas</li>
        <li>Akses berbasis role (Admin, Guru, Siswa)</li>
        <li>Laporan akademik otomatis</li>
      </ul>
    </div>

    <!-- RIGHT (STATUS) -->
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <div class="text-4xl mb-4">🚧</div>

      <h3 class="text-xl font-semibold mb-4">
        Status Pengembangan
      </h3>

      <p class="text-gray-600 mb-6">
        Sistem Akademik ini sudah dapat dicoba melalui versi demo
        untuk melihat alur dan fitur utama aplikasi.
      </p>

      <div class="flex flex-col gap-4">
        <!-- DEMO BUTTON -->
        <a
          href="https://siakad-theta.vercel.app/"
          target="_blank"
          rel="noopener"
          class="inline-block text-center px-6 py-3 rounded-xl
                 bg-blue-600 text-white hover:bg-blue-700
                 transition font-semibold"
        >
          🚀 Coba Demo Sistem Akademik
        </a>

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
          Konsultasi Sistem Akademik
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Butuh Sistem Akademik untuk Sekolah Anda?
      </h2>

      <p class="text-gray-600 max-w-xl mx-auto mb-8">
        Kami siap membantu membangun sistem akademik yang
        aman, scalable, dan mudah digunakan.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-black text-white px-8 py-4
               rounded-xl font-semibold hover:bg-gray-800 transition"
      >
        Diskusi Sekarang
      </NuxtLink>
    </div>
  </section>
</template>
