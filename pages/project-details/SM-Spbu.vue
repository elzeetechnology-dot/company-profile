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
        Sistem Manajemen SPBU
      </h1>

      <p class="text-gray-300 max-w-2xl mx-auto text-lg">
        Sistem manajemen berbasis web untuk membantu operasional SPBU
        menjadi lebih terkontrol, akurat, dan transparan.
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
        Sistem Manajemen SPBU ini dikembangkan untuk membantu pemilik
        dan pengelola SPBU dalam memantau stok BBM, transaksi harian,
        serta laporan penjualan secara real-time.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Monitoring stok BBM secara akurat</li>
        <li>Pencatatan transaksi harian</li>
        <li>Laporan penjualan otomatis</li>
        <li>Manajemen user & role</li>
        <li>Data tersimpan aman & terstruktur</li>
      </ul>
    </div>

    <!-- RIGHT -->
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <h3 class="text-xl font-semibold mb-4">
        Fitur Utama Sistem
      </h3>

      <ul class="space-y-4 text-gray-600 mb-6">
        <li>• Dashboard monitoring real-time</li>
        <li>• Stok masuk & keluar BBM</li>
        <li>• Rekap transaksi harian & bulanan</li>
        <li>• Hak akses (Owner / Supervisor / Admin)</li>
        <li>• Export laporan (PDF / Excel)</li>
      </ul>

      <div class="flex flex-col gap-4">
  <!-- 🔥 DEMO BUTTON -->
  <a
    href="https://adminspbu.online/"
    target="_blank"
    rel="noopener noreferrer"
    class="inline-block text-center px-6 py-3 rounded-xl
           bg-emerald-600 text-white hover:bg-emerald-700
           transition font-semibold"
  >
    ⛽ Lihat Demo Sistem SPBU
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
    Konsultasi Sistem SPBU
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
            Laravel / REST API
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Database</h4>
          <p class="text-sm text-gray-600">
            MySQL / Relational Database
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- BENEFITS -->
  <section>
    <div class="max-w-6xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-12">
        Manfaat untuk Pengelola SPBU
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Lebih Akurat</h4>
          <p class="text-sm text-gray-600">
            Data stok & transaksi tercatat otomatis
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Lebih Transparan</h4>
          <p class="text-sm text-gray-600">
            Owner dapat memantau laporan kapan saja
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Lebih Efisien</h4>
          <p class="text-sm text-gray-600">
            Minim kesalahan pencatatan manual
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- STATUS -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-20 text-center">
      <div class="text-4xl mb-4">⛽</div>

      <h2 class="text-2xl font-semibold mb-4">
        Status Project
      </h2>

      <p class="text-gray-600 max-w-xl mx-auto">
        Sistem Manajemen SPBU ini telah diimplementasikan
        dan dapat dikembangkan lebih lanjut sesuai kebutuhan
        operasional setiap SPBU.
      </p>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Butuh Sistem Manajemen SPBU?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Kami siap membantu membangun sistem SPBU yang aman,
        akurat, dan mudah digunakan.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-8 py-4
               rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Konsultasi Gratis
      </NuxtLink>
    </div>
  </section>
</template>
