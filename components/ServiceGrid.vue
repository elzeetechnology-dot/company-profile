<template>
  <section class="py-24 bg-gray-50">
    <div class="max-w-7xl mx-auto px-6">
      <!-- Section title -->
      <div class="text-center max-w-2xl mx-auto mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">
          Layanan Kami
        </h2>
        <p class="text-gray-600 text-lg">
          Solusi digital end-to-end untuk membantu bisnis Anda tumbuh
          lebih cepat dan efisien.
        </p>
      </div>

      <!-- Services grid -->
      <div class="grid gap-8 md:grid-cols-3">

        <!-- Card 1 -->
        <NuxtLink
          to="/service-details/company-profile"
          class="group bg-white p-8 rounded-2xl shadow-sm
                 hover:shadow-xl transition-all duration-300
                 hover:-translate-y-2 block"
        >
          <div
            class="w-12 h-12 flex items-center justify-center rounded-xl
                   bg-blue-100 text-blue-600 mb-6
                   group-hover:bg-blue-600 group-hover:text-white transition"
          >
            🌐
          </div>

          <h3 class="text-xl font-semibold mb-3">
            Website Company Profile
          </h3>
          <p class="text-gray-600 leading-relaxed">
            Website profesional untuk meningkatkan kredibilitas dan
            kepercayaan pelanggan terhadap bisnis Anda.
          </p>
        </NuxtLink>

        <!-- Card 2 -->
        <NuxtLink
          to="/service-details/web-application"
          class="group bg-white p-8 rounded-2xl shadow-sm
                 hover:shadow-xl transition-all duration-300
                 hover:-translate-y-2 block"
        >
          <div
            class="w-12 h-12 flex items-center justify-center rounded-xl
                   bg-indigo-100 text-indigo-600 mb-6
                   group-hover:bg-indigo-600 group-hover:text-white transition"
          >
            ⚙️
          </div>

          <h3 class="text-xl font-semibold mb-3">
            Web Application
          </h3>
          <p class="text-gray-600 leading-relaxed">
            Sistem berbasis web yang disesuaikan dengan kebutuhan
            operasional perusahaan Anda.
          </p>
        </NuxtLink>

        <!-- Card 3 -->
        <NuxtLink
          to="/service-details/mobile-application"
          class="group bg-white p-8 rounded-2xl shadow-sm
                 hover:shadow-xl transition-all duration-300
                 hover:-translate-y-2 block"
        >
          <div
            class="w-12 h-12 flex items-center justify-center rounded-xl
                   bg-purple-100 text-purple-600 mb-6
                   group-hover:bg-purple-600 group-hover:text-white transition"
          >
            📱
          </div>

          <h3 class="text-xl font-semibold mb-3">
            Mobile Application
          </h3>
          <p class="text-gray-600 leading-relaxed">
            Aplikasi Android & iOS modern dengan performa tinggi dan
            pengalaman pengguna yang optimal.
          </p>
        </NuxtLink>

      </div>
    </div>
  </section>
</template>
