<template>
  <!-- HERO -->
  <section class="bg-gradient-to-b from-gray-50 to-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm font-medium text-blue-600 bg-blue-50 rounded-full"
      >
        Services
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Solusi Digital untuk Bisnis Modern
      </h1>

      <p class="text-gray-600 max-w-2xl mx-auto text-lg">
        Kami membantu UMKM, perusahaan, dan startup membangun sistem digital
        yang efisien, aman, dan scalable.
      </p>
    </div>
  </section>

  <!-- SERVICES GRID -->
  <section class="max-w-7xl mx-auto px-6 py-20">
    <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">

      <!-- Company Profile -->
      <NuxtLink
        to="/service-details/company-profile"
        class="service-card block"
      >
        <h3>Website Company Profile</h3>
        <p>
          Website profesional untuk meningkatkan kredibilitas dan
          memperkuat branding bisnis Anda.
        </p>
        <ul>
          <li>Desain modern & responsif</li>
          <li>SEO friendly</li>
          <li>Mudah dikelola</li>
        </ul>
      </NuxtLink>

      <!-- Web Application -->
      <NuxtLink
        to="/service-details/web-application"
        class="service-card block"
      >
        <h3>Web Application</h3>
        <p>
          Aplikasi web custom sesuai kebutuhan operasional
          perusahaan dengan performa tinggi.
        </p>
        <ul>
          <li>Sistem internal perusahaan</li>
          <li>Dashboard & reporting</li>
          <li>Aman & scalable</li>
        </ul>
      </NuxtLink>

      <!-- Mobile App -->
      <NuxtLink
        to="/service-details/mobile-application"
        class="service-card block"
      >
        <h3>Mobile App Development</h3>
        <p>
          Aplikasi Android & iOS untuk menjangkau pelanggan
          Anda secara lebih luas.
        </p>
        <ul>
          <li>Android & iOS</li>
          <li>UI/UX intuitif</li>
          <li>Performa optimal</li>
        </ul>
      </NuxtLink>

      <!-- UI UX -->
      <NuxtLink
        to="/service-details/uiux-design"
        class="service-card block"
      >
        <h3>UI / UX Design</h3>
        <p>
          Desain antarmuka yang fokus pada pengalaman pengguna
          dan peningkatan konversi.
        </p>
        <ul>
          <li>User research</li>
          <li>Wireframe & prototype</li>
          <li>Design system</li>
        </ul>
      </NuxtLink>

      <!-- Maintenance -->
      <NuxtLink
        to="/service-details/maintenance-support"
        class="service-card block"
      >
        <h3>Maintenance & Support</h3>
        <p>
          Layanan maintenance untuk memastikan sistem
          selalu stabil dan aman.
        </p>
        <ul>
          <li>Bug fixing</li>
          <li>Update sistem</li>
          <li>Monitoring</li>
        </ul>
      </NuxtLink>

      <!-- Highlight Card -->
      <div
        class="rounded-2xl p-8 bg-black text-white hover:-translate-y-2 transition duration-300"
      >
        <h3 class="text-xl font-semibold mb-4">
          Konsultasi Digital
        </h3>
        <p class="text-gray-300 mb-6">
          Diskusikan kebutuhan digital Anda bersama tim kami
          untuk mendapatkan solusi terbaik.
        </p>
        <ul class="text-sm text-gray-300 space-y-2 mb-6">
          <li>Analisis kebutuhan</li>
          <li>Rekomendasi teknologi</li>
          <li>Strategi digital</li>
        </ul>

        <NuxtLink
          to="/contact"
          class="inline-block bg-white text-black px-6 py-3 rounded-xl font-semibold hover:bg-gray-200 transition"
        >
          Konsultasi Gratis
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-gray-900 text-white">
    <div class="max-w-7xl mx-auto px-6 py-20 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        Siap Memulai Proyek Digital Anda?
      </h2>
      <p class="text-gray-400 max-w-xl mx-auto mb-8">
        Hubungi kami sekarang dan dapatkan solusi digital
        yang tepat untuk bisnis Anda.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-blue-600 px-8 py-4 rounded-xl font-semibold hover:bg-blue-700 transition"
      >
        Hubungi Kami
      </NuxtLink>
    </div>
  </section>
</template>

<style scoped>
.service-card {
  @apply border rounded-2xl p-8 bg-white
    hover:shadow-xl hover:-translate-y-2
    transition duration-300 cursor-pointer;
}

.service-card h3 {
  @apply text-xl font-semibold mb-4;
}

.service-card p {
  @apply text-gray-600 mb-4;
}

.service-card ul {
  @apply text-sm text-gray-600 space-y-2;
}
</style>
