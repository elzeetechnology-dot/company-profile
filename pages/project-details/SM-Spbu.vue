<template>
  <!-- HERO -->
  <section class="relative bg-gradient-to-br from-gray-900 to-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <span class="inline-block mb-4 text-sm tracking-wide text-gray-300 uppercase">
        Layanan Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
        Website Company Profile <br class="hidden md:block" />
        yang Profesional & Kredibel
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-gray-300 mb-10">
        Kami membantu bisnis membangun identitas digital yang kuat melalui
        website company profile modern, cepat, dan siap berkembang.
      </p>

      <div class="flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="bg-white text-black px-7 py-3 rounded-xl font-semibold
                 hover:bg-gray-200 transition"
        >
          Konsultasi Gratis
        </NuxtLink>

        <NuxtLink
          to="/portfolio"
          class="border border-white/30 px-7 py-3 rounded-xl
                 hover:bg-white hover:text-black transition"
        >
          Lihat Portfolio
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16 items-start">
    <!-- Left -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">
        Apa yang Kami Kerjakan?
      </h2>

      <p class="text-gray-600 mb-6 leading-relaxed">
        Website company profile bukan hanya sekadar tampilan,
        tetapi representasi profesional dari brand Anda.
        Kami merancang website yang fokus pada kejelasan informasi,
        kredibilitas, dan pengalaman pengguna.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Desain modern & mobile-friendly</li>
        <li>Struktur halaman rapi dan mudah dipahami</li>
        <li>Optimasi SEO dasar</li>
        <li>Performa cepat & ringan</li>
        <li>Siap dikembangkan ke fitur lanjutan</li>
      </ul>
    </div>

    <!-- Right -->
    <div class="bg-white rounded-2xl shadow-sm p-10">
      <h3 class="text-xl font-semibold mb-6">
        Fitur Standar
      </h3>

      <div class="grid grid-cols-2 gap-4 text-sm text-gray-600">
        <div class="flex gap-2">✅ Home & Landing Page</div>
        <div class="flex gap-2">✅ About Company</div>
        <div class="flex gap-2">✅ Services Page</div>
        <div class="flex gap-2">✅ Portfolio / Project</div>
        <div class="flex gap-2">✅ Contact & Form</div>
        <div class="flex gap-2">✅ WhatsApp Integration</div>
        <div class="flex gap-2">✅ Google Maps</div>
        <div class="flex gap-2">✅ SEO Friendly</div>
      </div>

      <NuxtLink
        to="/contact"
        class="inline-block mt-10 bg-black text-white px-6 py-3
               rounded-xl hover:bg-gray-800 transition font-semibold"
      >
        Konsultasi Website
      </NuxtLink>
    </div>
  </section>

  <!-- PROCESS -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-14">
        Proses Pengerjaan
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-4 gap-8">
        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">📋</div>
          <h4 class="font-semibold mb-2">Analisis</h4>
          <p class="text-sm text-gray-600">
            Diskusi kebutuhan & tujuan bisnis Anda
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">🎨</div>
          <h4 class="font-semibold mb-2">Desain</h4>
          <p class="text-sm text-gray-600">
            Desain UI/UX yang modern & relevan
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">💻</div>
          <h4 class="font-semibold mb-2">Development</h4>
          <p class="text-sm text-gray-600">
            Implementasi teknis & optimasi performa
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">🚀</div>
          <h4 class="font-semibold mb-2">Launch</h4>
          <p class="text-sm text-gray-600">
            Website siap online & digunakan
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA BOTTOM -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Siap Membangun Website Company Profile?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Diskusikan kebutuhan website bisnis Anda bersama tim kami
        dan dapatkan solusi terbaik.
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
