<template>
  <!-- HERO -->
  <section class="bg-gradient-to-b from-gray-50 to-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm font-medium
               text-blue-600 bg-blue-50 rounded-full"
      >
        Portfolio
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Project yang Telah Kami Kerjakan
      </h1>

      <p class="text-gray-600 max-w-2xl mx-auto text-lg">
        Kami telah membantu UMKM, sekolah, perusahaan, hingga startup
        membangun sistem digital yang efektif dan berkelanjutan.
      </p>
    </div>
  </section>

  <!-- PORTFOLIO GRID -->
  <section class="max-w-7xl mx-auto px-6 py-20">
    <div class="grid gap-10 sm:grid-cols-2 lg:grid-cols-3">
      <NuxtLink
        v-for="item in portfolios"
        :key="item.title"
        :to="item.link"
        class="group rounded-2xl overflow-hidden bg-white border
               hover:shadow-2xl transition duration-300"
      >
        <!-- IMAGE -->
        <div class="relative h-52 overflow-hidden">
  <img
    :src="item.image"
    :alt="item.title"
    class="w-full h-full object-cover
           group-hover:scale-105 transition duration-500"
  />

  <!-- Overlay -->
  <div
    class="absolute inset-0 bg-black/60 opacity-0
           group-hover:opacity-100 transition
           flex items-center justify-center"
  >
    <span class="text-white font-semibold tracking-wide">
      View Project →
    </span>
  </div>
</div>

        <!-- CONTENT -->
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">
            {{ item.title }}
          </h3>

          <p class="text-gray-600 text-sm mb-4">
            {{ item.description }}
          </p>

          <div class="flex flex-wrap gap-2">
            <span
              v-for="tech in item.tech"
              :key="tech"
              class="text-xs bg-gray-100
                     text-gray-700 px-3 py-1 rounded-full"
            >
              {{ tech }}
            </span>
          </div>
        </div>
      </NuxtLink>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-gray-900 text-white">
    <div class="max-w-7xl mx-auto px-6 py-20 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        Punya Ide Project?
      </h2>

      <p class="text-gray-400 max-w-xl mx-auto mb-8">
        Diskusikan kebutuhan Anda bersama tim kami
        dan wujudkan solusi digital terbaik.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-blue-600 px-8 py-4
               rounded-xl font-semibold
               hover:bg-blue-700 transition"
      >
        Konsultasi Gratis
      </NuxtLink>
    </div>
  </section>
</template>

<script setup>
const portfolios = [
  {
    title: 'Sistem Manajemen SPBU',
    description:
      'Aplikasi web untuk monitoring stok, penjualan, dan laporan harian SPBU.',
    tech: ['Vue', 'Laravel', 'MySQL'],
    link: '/project-details/SM-Spbu',
    image: '/images/portfolio/spbu-admin.png',
    demo: 'https://adminspbu.online/',
  },
  {
    title: 'Website Company Profile',
    description:
      'Website profesional untuk meningkatkan branding dan kepercayaan perusahaan.',
    tech: ['Nuxt', 'Tailwind CSS'],
    link: '/project-details/Company-profile',
    image: '/images/portfolio/company-profile.png',
    demo: 'https://elzeetechnology.vercel.app/',
  },
  {
    title: 'Aplikasi Kasir UMKM',
    description:
      'Aplikasi kasir berbasis web untuk membantu pencatatan transaksi UMKM.',
    tech: ['Vue', 'Firebase'],
    link: '/project-details/UMKM',
    image: '/images/portfolio/umkm.png',
    demo: 'https://umkm-app-gold.vercel.app/',
  },
  {
    title: 'Sistem Akademik Sekolah',
    description:
      'Pengelolaan data siswa, guru, nilai, dan laporan akademik.',
    tech: ['Laravel', 'Bootstrap'],
    link: '/project-details/Akademik',
    image: '/images/portfolio/comingsoon.png',
  },
  {
    title: 'Dashboard Admin',
    description:
      'Dashboard admin untuk manajemen data dan monitoring sistem.',
    tech: ['Nuxt', 'API', 'Tailwind'],
    link: '/project-details/Admin',
    image: '/images/portfolio/comingsoon.png',
  },
  {
    title: 'Aplikasi Booking Online',
    description:
      'Sistem booking layanan online dengan notifikasi dan manajemen jadwal.',
    tech: ['Vue', 'Node.js'],
    link: '/project-details/Book-app',
    image: '/images/portfolio/comingsoon.png',
  },
]

</script>
