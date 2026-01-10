<template>
  <!-- HERO -->
  <section class="relative bg-gradient-to-br from-purple-900 to-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <span class="inline-block mb-4 text-sm tracking-wide text-purple-300 uppercase">
        Layanan Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
        Mobile Application <br class="hidden md:block" />
        Android & iOS
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-purple-200 mb-10">
        Bangun aplikasi mobile modern untuk menjangkau pelanggan lebih luas
        dengan performa tinggi dan pengalaman pengguna terbaik.
      </p>

      <div class="flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="bg-white text-black px-7 py-3 rounded-xl font-semibold
                 hover:bg-gray-200 transition"
        >
          Konsultasi Mobile App
        </NuxtLink>

        <NuxtLink
          to="/portfolio"
          class="border border-white/30 px-7 py-3 rounded-xl
                 hover:bg-white hover:text-black transition"
        >
          Lihat Portofolio
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16 items-start">
    <!-- Left -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">
        Pengembangan Mobile Application
      </h2>

      <p class="text-gray-600 mb-6 leading-relaxed">
        Mobile application memungkinkan bisnis Anda hadir langsung
        di genggaman pengguna. Kami mengembangkan aplikasi yang fokus
        pada stabilitas, kecepatan, dan kemudahan penggunaan.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Aplikasi Android & iOS (single codebase)</li>
        <li>UI/UX modern & user-friendly</li>
        <li>Integrasi API & backend system</li>
        <li>Push notification & real-time update</li>
        <li>Optimal untuk performa & battery usage</li>
      </ul>
    </div>

    <!-- Right -->
    <div class="bg-white rounded-2xl shadow-sm p-10">
      <h3 class="text-xl font-semibold mb-6">
        Teknologi & Standar
      </h3>

      <div class="grid grid-cols-2 gap-4 text-sm text-gray-600">
        <div class="flex gap-2">✅ Android & iOS</div>
        <div class="flex gap-2">✅ Cross-platform</div>
        <div class="flex gap-2">✅ API-based System</div>
        <div class="flex gap-2">✅ Secure Authentication</div>
        <div class="flex gap-2">✅ Push Notification</div>
        <div class="flex gap-2">✅ Clean Architecture</div>
        <div class="flex gap-2">✅ Scalable Backend</div>
        <div class="flex gap-2">✅ App Store Ready</div>
      </div>

      <NuxtLink
        to="/contact"
        class="inline-block mt-10 bg-black text-white px-6 py-3
               rounded-xl hover:bg-gray-800 transition font-semibold"
      >
        Diskusi Mobile App
      </NuxtLink>
    </div>
  </section>

  <!-- USE CASES -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-14">
        Cocok Untuk Berbagai Kebutuhan
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Aplikasi Layanan</h4>
          <p class="text-sm text-gray-600">
            Booking, delivery, konsultasi, dan layanan berbasis mobile.
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Aplikasi Internal</h4>
          <p class="text-sm text-gray-600">
            Operasional lapangan, sales, dan monitoring internal perusahaan.
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Startup & Produk Digital</h4>
          <p class="text-sm text-gray-600">
            MVP hingga produk skala besar untuk pasar luas.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- PROCESS -->
  <section>
    <div class="max-w-7xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-14">
        Proses Pengembangan
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-4 gap-8">
        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">📱</div>
          <h4 class="font-semibold mb-2">Concept</h4>
          <p class="text-sm text-gray-600">
            Diskusi ide & kebutuhan aplikasi
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">🎨</div>
          <h4 class="font-semibold mb-2">UI/UX</h4>
          <p class="text-sm text-gray-600">
            Desain tampilan & user experience
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">⚙️</div>
          <h4 class="font-semibold mb-2">Development</h4>
          <p class="text-sm text-gray-600">
            Implementasi fitur & integrasi backend
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">🚀</div>
          <h4 class="font-semibold mb-2">Release</h4>
          <p class="text-sm text-gray-600">
            Testing, publish & maintenance
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Siap Membangun Aplikasi Mobile?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Konsultasikan ide aplikasi Anda bersama tim kami
        dan wujudkan produk mobile yang siap bersaing.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-8 py-4
               rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Konsultasi Sekarang
      </NuxtLink>
    </div>
  </section>
</template>
