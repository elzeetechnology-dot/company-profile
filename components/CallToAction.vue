<template>
  <section class="relative overflow-hidden py-28 bg-gradient-to-r from-blue-600 to-indigo-600 text-white">
    <!-- Decorative blur -->
    <div class="absolute -top-24 -left-24 w-96 h-96 bg-white/10 rounded-full blur-3xl"></div>
    <div class="absolute -bottom-24 -right-24 w-96 h-96 bg-white/10 rounded-full blur-3xl"></div>

    <div class="relative max-w-7xl mx-auto px-6 text-center">
      <!-- Heading -->
      <h2
        class="text-3xl md:text-5xl font-bold mb-6 leading-tight"
      >
        Siap Membangun Website <br class="hidden md:block" />
        yang Profesional & Modern?
      </h2>

      <!-- Subtitle -->
      <p class="text-lg md:text-xl text-blue-100 mb-10 max-w-2xl mx-auto">
        Kami membantu UMKM, perusahaan, dan startup membangun website &
        aplikasi yang cepat, aman, dan scalable untuk jangka panjang.
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <a
          href="https://wa.me/6282123925828"
          target="_blank"
          class="group inline-flex items-center justify-center gap-2 bg-white text-blue-600 px-10 py-4 rounded-2xl font-semibold shadow-lg hover:shadow-2xl hover:-translate-y-1 transition-all duration-300"
        >
          Konsultasi Gratis
          <span class="group-hover:translate-x-1 transition">→</span>
        </a>

        <NuxtLink
          to="/portfolio"
          class="inline-flex items-center justify-center px-10 py-4 rounded-2xl font-semibold border border-white/60 hover:bg-white hover:text-blue-600 transition-all duration-300"
        >
          Lihat Portfolio
        </NuxtLink>
      </div>

      <!-- Trust text -->
      <p class="mt-10 text-sm text-blue-200">
        ✨ Konsultasi tanpa biaya • Respon cepat • Solusi sesuai kebutuhan
      </p>
    </div>
  </section>
</template>
