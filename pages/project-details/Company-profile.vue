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
        Website Company Profile
      </h1>

      <p class="text-gray-300 max-w-2xl mx-auto text-lg">
        Website profesional untuk membangun kredibilitas,
        meningkatkan branding, dan memperkuat kepercayaan
        pelanggan terhadap bisnis.
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
        Website Company Profile ini dikembangkan sebagai wajah digital
        perusahaan. Fokus utama adalah tampilan profesional, struktur
        informasi yang jelas, dan performa yang cepat di semua perangkat.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Desain modern & responsif</li>
        <li>Struktur halaman rapi & mudah dipahami</li>
        <li>Optimasi SEO dasar</li>
        <li>Integrasi WhatsApp & form kontak</li>
        <li>Siap dikembangkan ke fitur lanjutan</li>
      </ul>
    </div>

    <!-- RIGHT -->
    <div class="bg-white rounded-2xl shadow-lg p-10">
      <h3 class="text-xl font-semibold mb-4">
        Teknologi & Implementasi
      </h3>

      <ul class="space-y-4 text-gray-600 mb-6">
        <li>• Frontend modern (Nuxt / Vue)</li>
        <li>• Tailwind CSS untuk desain konsisten</li>
        <li>• Struktur SEO friendly</li>
        <li>• Performa cepat & ringan</li>
        <li>• Hosting siap production</li>
      </ul>

      <div class="flex flex-col gap-4">
  <!-- 🔥 DEMO BUTTON -->
  <a
    href="https://elzeetechnology.vercel.app/"
    target="_blank"
    rel="noopener noreferrer"
    class="inline-block text-center px-6 py-3 rounded-xl
           bg-emerald-600 text-white hover:bg-emerald-700
           transition font-semibold"
  >
    🌐 Lihat Demo Website
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
    Buat Website Serupa
  </NuxtLink>
</div>

    </div>
  </section>

  <!-- USE CASE -->
  <section class="bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-12">
        Cocok Digunakan Untuk
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Perusahaan</h4>
          <p class="text-sm text-gray-600">
            Meningkatkan kredibilitas & branding
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">UMKM</h4>
          <p class="text-sm text-gray-600">
            Tampil profesional & dipercaya pelanggan
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm text-center">
          <h4 class="font-semibold mb-2">Startup</h4>
          <p class="text-sm text-gray-600">
            Validasi bisnis & presentasi ke investor
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- STATUS -->
  <section>
    <div class="max-w-6xl mx-auto px-6 py-20 text-center">
      <div class="text-4xl mb-4">🧩</div>

      <h2 class="text-2xl font-semibold mb-4">
        Status Project
      </h2>

      <p class="text-gray-600 max-w-xl mx-auto">
        Website Company Profile ini merupakan contoh implementasi
        yang terus dapat dikembangkan sesuai kebutuhan klien,
        baik dari sisi fitur maupun desain.
      </p>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-6xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Ingin Website Company Profile Profesional?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Kami siap membantu membangun website yang mencerminkan
        identitas dan nilai bisnis Anda.
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
