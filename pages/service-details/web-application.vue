<template>
  <!-- HERO -->
  <section class="relative bg-gradient-to-br from-indigo-900 to-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <span class="inline-block mb-4 text-sm tracking-wide text-indigo-300 uppercase">
        Layanan Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
        Web Application <br class="hidden md:block" />
        untuk Operasional Bisnis Modern
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-indigo-200 mb-10">
        Kami membangun aplikasi web custom yang aman, scalable,
        dan dirancang khusus untuk meningkatkan efisiensi bisnis Anda.
      </p>

      <div class="flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="bg-white text-black px-7 py-3 rounded-xl font-semibold
                 hover:bg-gray-200 transition"
        >
          Konsultasi Web App
        </NuxtLink>

        <NuxtLink
          to="/portfolio"
          class="border border-white/30 px-7 py-3 rounded-xl
                 hover:bg-white hover:text-black transition"
        >
          Lihat Studi Kasus
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- OVERVIEW -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16 items-start">
    <!-- Left -->
    <div>
      <h2 class="text-2xl font-semibold mb-4">
        Solusi Web Application
      </h2>

      <p class="text-gray-600 mb-6 leading-relaxed">
        Web application adalah tulang punggung sistem digital perusahaan.
        Kami merancang aplikasi yang fokus pada stabilitas, keamanan,
        dan kemudahan pengelolaan data untuk jangka panjang.
      </p>

      <ul class="space-y-3 text-gray-600 list-disc list-inside">
        <li>Sistem manajemen internal perusahaan</li>
        <li>Dashboard operasional & analytics</li>
        <li>Manajemen user, role & permission</li>
        <li>Workflow & automasi proses bisnis</li>
        <li>Integrasi API & layanan pihak ketiga</li>
      </ul>
    </div>

    <!-- Right -->
    <div class="bg-white rounded-2xl shadow-sm p-10">
      <h3 class="text-xl font-semibold mb-6">
        Teknologi & Standar
      </h3>

      <div class="grid grid-cols-2 gap-4 text-sm text-gray-600">
        <div class="flex gap-2">✅ Vue / Nuxt Frontend</div>
        <div class="flex gap-2">✅ API-based Backend</div>
        <div class="flex gap-2">✅ Auth & Role Management</div>
        <div class="flex gap-2">✅ Database Relational</div>
        <div class="flex gap-2">✅ Secure Architecture</div>
        <div class="flex gap-2">✅ Modular & Maintainable</div>
        <div class="flex gap-2">✅ Cloud-ready</div>
        <div class="flex gap-2">✅ Long-term Scalability</div>
      </div>

      <NuxtLink
        to="/contact"
        class="inline-block mt-10 bg-black text-white px-6 py-3
               rounded-xl hover:bg-gray-800 transition font-semibold"
      >
        Diskusi Web Application
      </NuxtLink>
    </div>
  </section>

  <!-- USE CASES -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-24">
      <h2 class="text-2xl font-semibold text-center mb-14">
        Contoh Use Case
      </h2>

      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Dashboard Manajemen</h4>
          <p class="text-sm text-gray-600">
            Monitoring data, performa, dan laporan bisnis secara real-time.
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Sistem Internal</h4>
          <p class="text-sm text-gray-600">
            HR, inventory, keuangan, dan sistem operasional lainnya.
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">SaaS Platform</h4>
          <p class="text-sm text-gray-600">
            Aplikasi berbasis langganan dengan multi-user dan billing.
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
          <div class="text-2xl mb-3">🧠</div>
          <h4 class="font-semibold mb-2">Requirement</h4>
          <p class="text-sm text-gray-600">
            Analisis kebutuhan bisnis & sistem
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">📐</div>
          <h4 class="font-semibold mb-2">Architecture</h4>
          <p class="text-sm text-gray-600">
            Desain struktur & flow aplikasi
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">⚙️</div>
          <h4 class="font-semibold mb-2">Development</h4>
          <p class="text-sm text-gray-600">
            Implementasi fitur & integrasi sistem
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl shadow-sm text-center">
          <div class="text-2xl mb-3">🚀</div>
          <h4 class="font-semibold mb-2">Deployment</h4>
          <p class="text-sm text-gray-600">
            Testing, optimasi, dan go-live
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Butuh Web Application Custom?
      </h2>

      <p class="text-gray-300 max-w-xl mx-auto mb-8">
        Diskusikan sistem yang ingin Anda bangun bersama tim kami
        dan dapatkan solusi yang tepat & scalable.
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
