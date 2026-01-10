<template>
  <!-- HERO -->
  <section class="relative bg-gradient-to-br from-gray-900 via-black to-gray-900 text-white overflow-hidden">
    <div class="absolute inset-0 opacity-20 bg-[radial-gradient(circle_at_top,rgba(255,255,255,0.15),transparent_60%)]"></div>

    <div class="relative max-w-7xl mx-auto px-6 py-32 text-center">
      <span class="inline-block mb-5 text-xs tracking-widest text-gray-400 uppercase">
        Layanan Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
        Maintenance & Support
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-gray-300">
        Pastikan sistem digital Anda selalu aman, stabil, dan siap
        mendukung pertumbuhan bisnis tanpa gangguan teknis.
      </p>

      <div class="mt-10 flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="bg-white text-black px-8 py-3 rounded-xl font-semibold hover:bg-gray-200 transition"
        >
          Konsultasi Gratis
        </NuxtLink>

        <NuxtLink
          to="/portfolio"
          class="border border-white/30 px-8 py-3 rounded-xl text-white hover:bg-white hover:text-black transition"
        >
          Lihat Project
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-7xl mx-auto px-6 py-28 grid md:grid-cols-2 gap-16 items-start">
    <div>
      <h2 class="text-2xl font-semibold mb-6">
        Menjaga Sistem Tetap Optimal
      </h2>

      <p class="text-gray-600 mb-6 leading-relaxed">
        Sistem digital yang tidak dirawat akan menimbulkan bug,
        celah keamanan, dan penurunan performa. Kami hadir sebagai
        partner teknis jangka panjang untuk memastikan sistem Anda
        selalu dalam kondisi terbaik.
      </p>

      <ul class="space-y-4 text-gray-600 list-disc list-inside">
        <li>Monitoring performa & server 24/7</li>
        <li>Bug fixing & troubleshooting cepat</li>
        <li>Update keamanan & dependency</li>
        <li>Backup data terjadwal</li>
        <li>Dukungan teknis berkelanjutan</li>
      </ul>
    </div>

    <div class="bg-white rounded-2xl shadow-md p-10 border">
      <h3 class="text-xl font-semibold mb-6">
        Cakupan Layanan
      </h3>

      <ul class="space-y-4 text-gray-600">
        <li>• Website & Web Application</li>
        <li>• Mobile Application (Android & iOS)</li>
        <li>• API & backend service</li>
        <li>• Update framework & library</li>
        <li>• Konsultasi teknis berkala</li>
      </ul>

      <NuxtLink
        to="/contact"
        class="inline-block mt-10 bg-black text-white px-6 py-3 rounded-xl hover:bg-gray-800 transition"
      >
        Diskusi Maintenance
      </NuxtLink>
    </div>
  </section>

  <!-- PROCESS -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-28">
      <h2 class="text-2xl font-semibold text-center mb-16">
        Alur Kerja Maintenance
      </h2>

      <div class="grid md:grid-cols-4 gap-8 text-center">
        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Audit Sistem</h4>
          <p class="text-sm text-gray-600">
            Analisis kondisi sistem & risiko teknis
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Monitoring</h4>
          <p class="text-sm text-gray-600">
            Pemantauan performa & keamanan
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Perbaikan</h4>
          <p class="text-sm text-gray-600">
            Bug fixing & optimasi sistem
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Evaluasi</h4>
          <p class="text-sm text-gray-600">
            Laporan & rekomendasi lanjutan
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- BENEFITS -->
  <section class="max-w-7xl mx-auto px-6 py-28">
    <h2 class="text-2xl font-semibold text-center mb-16">
      Keuntungan Maintenance & Support
    </h2>

    <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-10">
      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Keamanan Terjaga</h4>
        <p class="text-sm text-gray-600">
          Update keamanan rutin mencegah celah & serangan
        </p>
      </div>

      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Sistem Stabil</h4>
        <p class="text-sm text-gray-600">
          Risiko downtime & error dapat diminimalkan
        </p>
      </div>

      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Fokus ke Bisnis</h4>
        <p class="text-sm text-gray-600">
          Anda fokus strategi, kami urus teknis
        </p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        Sistem Anda Perlu Perawatan Profesional?
      </h2>

      <p class="text-gray-300 mb-10 max-w-xl mx-auto">
        Percayakan maintenance & support sistem digital Anda kepada tim
        yang berpengalaman dan berorientasi jangka panjang.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-10 py-4 rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Konsultasi Sekarang
      </NuxtLink>
    </div>
  </section>
</template>
