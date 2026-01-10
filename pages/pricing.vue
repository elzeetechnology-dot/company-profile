<template>
  <!-- HERO -->
  <section class="bg-gradient-to-br from-gray-900 to-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-28 text-center">
      <span class="inline-block mb-4 text-sm tracking-wide text-gray-400 uppercase">
        Pricing
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Harga Transparan, Kualitas Maksimal
      </h1>

      <p class="max-w-2xl mx-auto text-lg text-gray-300">
        Pilih paket layanan yang sesuai dengan kebutuhan bisnis Anda.
        Harga fleksibel, hasil profesional.
      </p>
    </div>
  </section>

  <!-- COMPANY PROFILE -->
  <section class="max-w-7xl mx-auto px-6 py-24">
    <h2 class="section-title">Website Company Profile</h2>

    <div class="pricing-grid">
      <PricingCard
        title="Starter"
        price="2.500.000"
        desc="Cocok untuk UMKM & personal brand"
        :features="[
          '5 halaman utama',
          'Desain responsif',
          'Form kontak',
          'Integrasi WhatsApp',
          'Basic SEO'
        ]"
      />

      <PricingCard
        title="Business"
        price="4.500.000"
        highlight
        desc="Pilihan terbaik untuk bisnis berkembang"
        :features="[
          '8–10 halaman',
          'Desain premium',
          'SEO optimization',
          'Google Maps',
          'CMS / admin sederhana'
        ]"
      />

      <PricingCard
        title="Premium"
        price="7.500.000"
        desc="Untuk perusahaan & brand profesional"
        :features="[
          'Unlimited halaman',
          'Custom UI/UX',
          'Advanced SEO',
          'Performance optimization',
          'Siap dikembangkan'
        ]"
      />
    </div>
  </section>

  <!-- WEB APPLICATION -->
  <section class="bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 py-24">
      <h2 class="section-title">Web Application</h2>

      <div class="pricing-grid">
        <PricingCard
          title="Basic System"
          price="8.000.000"
          desc="Sistem sederhana & internal"
          :features="[
            'CRUD system',
            'Login & role',
            'Dashboard basic',
            'Database integration'
          ]"
        />

        <PricingCard
          title="Business App"
          price="15.000.000"
          highlight
          desc="Aplikasi bisnis siap pakai"
          :features="[
            'Custom flow',
            'Dashboard & report',
            'Role management',
            'API ready',
            'Secure authentication'
          ]"
        />

        <PricingCard
          title="Enterprise"
          price="Custom"
          desc="Skala besar & kompleks"
          :features="[
            'Custom architecture',
            'Scalable system',
            'Advanced security',
            'Maintenance ready'
          ]"
        />
      </div>
    </div>
  </section>

  <!-- MOBILE APP -->
  <section class="max-w-7xl mx-auto px-6 py-24">
    <h2 class="section-title">Mobile Application</h2>

    <div class="pricing-grid">
      <PricingCard
        title="MVP App"
        price="15.000.000"
        desc="Validasi ide & startup"
        :features="[
          'Android / iOS',
          'Core feature',
          'API integration',
          'Simple UI'
        ]"
      />

      <PricingCard
        title="Business App"
        price="25.000.000"
        highlight
        desc="Aplikasi siap market"
        :features="[
          'Android & iOS',
          'Custom UI/UX',
          'Push notification',
          'Secure backend'
        ]"
      />

      <PricingCard
        title="Enterprise"
        price="Custom"
        desc="Aplikasi skala besar"
        :features="[
          'High performance',
          'Real-time feature',
          'Advanced security',
          'Maintenance ready'
        ]"
      />
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <h2 class="text-3xl font-bold mb-4">
        Butuh Paket Custom?
      </h2>
      <p class="text-gray-300 mb-8 max-w-xl mx-auto">
        Diskusikan kebutuhan Anda, kami bantu tentukan solusi terbaik.
      </p>

      <NuxtLink
        to="/contact"
        class="inline-block bg-white text-black px-8 py-4 rounded-xl font-semibold hover:bg-gray-200 transition"
      >
        Konsultasi Gratis
      </NuxtLink>
    </div>
  </section>
</template>

<script setup>
import PricingCard from '~/components/PricingCard.vue'
</script>

<style scoped>
.section-title {
  @apply text-3xl font-bold text-center mb-12;
}

.pricing-grid {
  @apply grid gap-8 md:grid-cols-3;
}
</style>
