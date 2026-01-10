<template>
  <!-- HERO -->
  <section class="relative bg-gradient-to-br from-gray-900 via-black to-gray-900 text-white overflow-hidden">
    <div class="absolute inset-0 opacity-20 bg-[radial-gradient(circle_at_top,rgba(255,255,255,0.15),transparent_60%)]"></div>

    <div class="relative max-w-7xl mx-auto px-6 py-32 text-center">
      <span class="inline-block mb-5 text-xs tracking-widest text-gray-400 uppercase">
        Layanan Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
        UI / UX Design
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-gray-300">
        Desain yang tidak hanya indah, tetapi juga berfungsi.
        Kami merancang pengalaman pengguna yang meningkatkan
        engagement, efisiensi, dan konversi.
      </p>

      <div class="mt-10 flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="bg-white text-black px-8 py-3 rounded-xl font-semibold hover:bg-gray-200 transition"
        >
          Konsultasi UI/UX
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
        Fokus Pada Pengguna
      </h2>

      <p class="text-gray-600 mb-6 leading-relaxed">
        UI/UX bukan sekadar tampilan visual. Kami merancang
        alur interaksi yang memudahkan pengguna mencapai tujuan
        mereka dengan cepat dan nyaman.
      </p>

      <ul class="space-y-4 text-gray-600 list-disc list-inside">
        <li>User research & persona berbasis data</li>
        <li>User flow & information architecture</li>
        <li>Wireframe & prototype interaktif</li>
        <li>Design system konsisten & scalable</li>
        <li>Usability testing & iterasi desain</li>
      </ul>
    </div>

    <div class="bg-white rounded-2xl shadow-md p-10 border">
      <h3 class="text-xl font-semibold mb-6">
        Tools & Deliverables
      </h3>

      <ul class="space-y-4 text-gray-600">
        <li>• Wireframe low & high fidelity</li>
        <li>• Prototype interaktif (Figma)</li>
        <li>• UI kit & design system</li>
        <li>• Dokumentasi handoff ke developer</li>
      </ul>

      <NuxtLink
        to="/contact"
        class="inline-block mt-10 bg-black text-white px-6 py-3 rounded-xl hover:bg-gray-800 transition"
      >
        Diskusi UI/UX
      </NuxtLink>
    </div>
  </section>

  <!-- PROCESS -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-28">
      <h2 class="text-2xl font-semibold text-center mb-16">
        Proses Desain Kami
      </h2>

      <div class="grid md:grid-cols-4 gap-8 text-center">
        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Research</h4>
          <p class="text-sm text-gray-600">
            Memahami pengguna & kebutuhan bisnis
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Structure</h4>
          <p class="text-sm text-gray-600">
            User flow & wireframe
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Design</h4>
          <p class="text-sm text-gray-600">
            Visual UI & prototype
          </p>
        </div>

        <div class="bg-white p-8 rounded-2xl shadow-sm">
          <h4 class="font-semibold mb-2">Testing</h4>
          <p class="text-sm text-gray-600">
            Validasi & iterasi desain
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- USE CASE -->
  <section class="max-w-7xl mx-auto px-6 py-28">
    <h2 class="text-2xl font-semibold text-center mb-16">
      Cocok Untuk
    </h2>

    <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-10">
      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Website Company Profile</h4>
        <p class="text-sm text-gray-600">
          Tampilan profesional & kredibel
        </p>
      </div>

      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Web Application</h4>
        <p class="text-sm text-gray-600">
          Flow pengguna yang efisien
        </p>
      </div>

      <div class="bg-white p-10 rounded-2xl shadow-sm text-center border">
        <h4 class="font-semibold mb-3">Mobile Application</h4>
        <p class="text-sm text-gray-600">
          UX nyaman & mudah digunakan
        </p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        Ingin Desain yang Lebih Efektif?
      </h2>

      <p class="text-gray-300 mb-10 max-w-xl mx-auto">
        Kami bantu menciptakan desain yang bukan hanya cantik,
        tapi juga memberikan hasil nyata untuk bisnis Anda.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-10 py-4 rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Mulai Konsultasi
      </NuxtLink>
    </div>
  </section>
</template>
