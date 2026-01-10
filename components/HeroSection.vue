<template>
  <section
    class="relative overflow-hidden bg-gradient-to-br from-blue-600 via-indigo-600 to-purple-700 text-white"
  >
    <!-- Decorative blur background -->
    <div class="absolute -top-32 -left-32 w-96 h-96 bg-white/10 rounded-full blur-3xl"></div>
    <div class="absolute bottom-0 right-0 w-96 h-96 bg-white/10 rounded-full blur-3xl"></div>

    <div
      class="relative max-w-7xl mx-auto px-6 py-28 text-center"
    >
      <!-- Badge -->
      <div
        class="inline-flex items-center gap-2 px-4 py-1 mb-6 rounded-full bg-white/10 backdrop-blur border border-white/20 text-sm"
      >
        🚀 Digital Solution Partner
      </div>

      <!-- Title -->
      <h1
        class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight mb-6 animate-fade-up"
      >
        Solusi Website & Aplikasi <br class="hidden md:block" />
        untuk Bisnis Anda
      </h1>

      <!-- Subtitle -->
      <p
        class="text-lg md:text-xl text-white/90 max-w-3xl mx-auto mb-10 animate-fade-up delay-150"
      >
        Kami membantu UMKM, sekolah, perusahaan, dan startup membangun
        sistem digital modern yang cepat, aman, dan scalable.
      </p>

      <!-- CTA Buttons -->
      <div
        class="flex flex-col sm:flex-row justify-center items-center gap-4 animate-fade-up delay-300"
      >
        <NuxtLink
          to="/contact"
          class="bg-white text-blue-600 px-8 py-4 rounded-xl font-semibold shadow-lg hover:shadow-xl hover:-translate-y-0.5 transition-all duration-300"
        >
          Konsultasi Gratis
        </NuxtLink>

        <NuxtLink
          to="/about"
          class="px-8 py-4 rounded-xl border border-white/70 hover:bg-white hover:text-blue-600 transition-all duration-300"
        >
          Tentang Kami
        </NuxtLink>

        <NuxtLink
          to="/services"
          class="px-8 py-4 rounded-xl border border-white/70 hover:bg-white hover:text-blue-600 transition-all duration-300"
        >
          Layanan Kami
        </NuxtLink>
      </div>
    </div>
  </section>
</template>
