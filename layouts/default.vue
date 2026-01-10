<script setup lang="ts">
import { ref } from 'vue'

const mobileOpen = ref(false)
const mobileServices = ref(false)
const mobilePortfolio = ref(false)
</script>


<template>
  <div class="min-h-screen flex flex-col bg-[#F6F3EE] text-gray-800">
    <!-- NAVBAR -->
    <header
      class="sticky top-0 z-50 bg-[#F6F3EE]/90 backdrop-blur
             border-b border-black/5"
    >
      <div
        class="max-w-7xl mx-auto px-2 py-5
               flex items-center justify-between flex-wrap"
      >
        <!-- BRAND -->
        <NuxtLink
          to="/"
          class="flex items-center gap-3 group"
        >
          <img
            src="/images/ELZEE.png"
            alt="ELZEE Technology Logo"
            class="h-11 w-auto transition-transform duration-300
                   group-hover:scale-105"
          />

          <span class="text-xl font-bold tracking-wide">
            ELZEE<span class="text-blue-600">.Technology</span>
          </span>
        </NuxtLink>

        <!-- DESKTOP MENU -->
        <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
          <NuxtLink to="/" class="nav-link">Home</NuxtLink>

          <!-- SERVICES DROPDOWN -->
          <div class="relative group">
            <button class="nav-link flex items-center gap-1">
              Services
              <span
                class="text-xs transition-transform duration-300
                       group-hover:rotate-180"
              >
                ▾
              </span>
            </button>

            <div
              class="absolute left-0 mt-4 w-72 rounded-2xl
                     bg-white shadow-2xl border border-black/5
                     opacity-0 invisible
                     group-hover:opacity-100 group-hover:visible
                     translate-y-3 group-hover:translate-y-0
                     transition-all duration-300 ease-out"
            >
              <ul class="py-3 text-sm">
                <li><NuxtLink to="/services" class="dropdown-link">Services</NuxtLink></li>
                <li><NuxtLink to="/service-details/company-profile" class="dropdown-link">Company Profile</NuxtLink></li>
                <li><NuxtLink to="/service-details/web-application" class="dropdown-link">Web Application</NuxtLink></li>
                <li><NuxtLink to="/service-details/mobile-application" class="dropdown-link">Mobile Application</NuxtLink></li>
                <li><NuxtLink to="/service-details/uiux-design" class="dropdown-link">UI / UX Design</NuxtLink></li>
                <li><NuxtLink to="/service-details/maintenance-support" class="dropdown-link">Maintenance & Support</NuxtLink></li>
              </ul>
            </div>
          </div>

          <!-- ✅ PRICING -->
          <NuxtLink to="/pricing" class="nav-link">
            Pricing
          </NuxtLink>

          <!-- PORTFOLIO DROPDOWN -->
          <div class="relative group">
            <button class="nav-link flex items-center gap-1">
              Portfolio
              <span
                class="text-xs transition-transform duration-300
                       group-hover:rotate-180"
              >
                ▾
              </span>
            </button>

            <div
              class="absolute left-0 mt-4 w-72 rounded-2xl
                     bg-white shadow-2xl border border-black/5
                     opacity-0 invisible
                     group-hover:opacity-100 group-hover:visible
                     translate-y-3 group-hover:translate-y-0
                     transition-all duration-300 ease-out"
            >
              <ul class="py-3 text-sm">
                <li><NuxtLink to="/portfolio" class="dropdown-link">Portfolio</NuxtLink></li>
                <li><NuxtLink to="/project-details/Admin" class="dropdown-link">Admin App</NuxtLink></li>
                <li><NuxtLink to="/project-details/Akademik" class="dropdown-link">Academy App</NuxtLink></li>
                <li><NuxtLink to="/project-details/Book-app" class="dropdown-link">Book App</NuxtLink></li>
                <li><NuxtLink to="/project-details/Company-profile" class="dropdown-link">Web App</NuxtLink></li>
                <li><NuxtLink to="/project-details/SM-Spbu" class="dropdown-link">SPBU App</NuxtLink></li>
                <li><NuxtLink to="/project-details/UMKM" class="dropdown-link">UMKM App</NuxtLink></li>
              </ul>
            </div>
          </div>
          <NuxtLink to="/about" class="nav-link">About</NuxtLink>
          <NuxtLink to="/contact" class="nav-link">Contact</NuxtLink>

          <!-- CTA -->
          <NuxtLink
            to="/contact"
            class="bg-black text-white px-6 py-2.5 rounded-xl
                   hover:bg-gray-800 transition font-semibold"
            :class="{ '!text-white': $route.path === '/contact' }"
          >
            Consultation
          </NuxtLink>
        </nav>
<!-- HAMBURGER BUTTON (MOBILE ONLY) -->
<button
  class="md:hidden flex flex-col justify-center gap-1
          ml-auto z-50"
  @click="mobileOpen = !mobileOpen"
  aria-label="Open menu"
>
  <span class="w-6 h-0.5 bg-black"></span>
  <span class="w-6 h-0.5 bg-black"></span>
  <span class="w-6 h-0.5 bg-black"></span>
</button>

        <!-- MOBILE MENU PANEL -->
<transition name="slide">
  <div
  v-if="mobileOpen"
  class="md:hidden fixed inset-0 z-40
         bg-[#F6F3EE]"
>
    <nav class="pt-24 px-6 space-y-4 text-sm font-medium">

      <NuxtLink to="/" class="mobile-link" @click="mobileOpen = false">
        Home
      </NuxtLink>

      <!-- SERVICES -->
      <button
        class="mobile-link w-full text-left flex justify-between"
        @click="mobileServices = !mobileServices"
      >
        Services
        <span>{{ mobileServices ? '−' : '+' }}</span>
      </button>

      <div v-if="mobileServices" class="ml-4 space-y-2">
        <NuxtLink to="/services" class="mobile-sub">Services</NuxtLink>
        <NuxtLink to="/service-details/company-profile" class="mobile-sub">Company Profile</NuxtLink>
        <NuxtLink to="/service-details/web-application" class="mobile-sub">Web Application</NuxtLink>
        <NuxtLink to="/service-details/mobile-application" class="mobile-sub">Mobile Application</NuxtLink>
        <NuxtLink to="/service-details/uiux-design" class="mobile-sub">UI / UX Design</NuxtLink>
        <NuxtLink to="/service-details/maintenance-support" class="mobile-sub">Maintenance & Support</NuxtLink>
      </div>

      <NuxtLink to="/pricing" class="mobile-link">
        Pricing
      </NuxtLink>

      <!-- PORTFOLIO -->
      <button
        class="mobile-link w-full text-left flex justify-between"
        @click="mobilePortfolio = !mobilePortfolio"
      >
        Portfolio
        <span>{{ mobilePortfolio ? '−' : '+' }}</span>
      </button>

      <div v-if="mobilePortfolio" class="ml-4 space-y-2">
        <NuxtLink to="/portfolio" class="mobile-sub">Portfolio</NuxtLink>
        <NuxtLink to="/project-details/Admin" class="mobile-sub">Admin App</NuxtLink>
        <NuxtLink to="/project-details/Akademik" class="mobile-sub">Academy App</NuxtLink>
        <NuxtLink to="/project-details/Book-app" class="mobile-sub">Book App</NuxtLink>
        <NuxtLink to="/project-details/Company-profile" class="mobile-sub">Web App</NuxtLink>
        <NuxtLink to="/project-details/SM-Spbu" class="mobile-sub">SPBU App</NuxtLink>
        <NuxtLink to="/project-details/UMKM" class="mobile-sub">UMKM App</NuxtLink>
      </div>

      <NuxtLink to="/about" class="mobile-link">
        About
      </NuxtLink>

      <NuxtLink to="/contact" class="mobile-link">
        Contact
      </NuxtLink>

      <!-- CTA -->
      <NuxtLink
        to="/contact"
        class="block mt-4 text-center bg-black text-white py-3 rounded-xl"
      >
        Consultation
      </NuxtLink>
    </nav>
  </div>
</transition>

      </div>
    </header>

    <!-- CONTENT -->
    <main class="flex-1">
      <slot />
    </main>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-400">
      <div
        class="max-w-7xl mx-auto px-6 py-14
               grid grid-cols-1
               md:grid-cols-[2fr_1fr_1fr_1fr]
               gap-x-14 gap-y-10"
      >
        <!-- ABOUT -->
        <div>
          <h3 class="text-white font-semibold mb-3">ELZEE Technology</h3>
          <p class="text-sm leading-relaxed mb-4">
            Partner teknologi terpercaya untuk pengembangan website,
            web application, dan mobile application dengan standar modern.
          </p>
          <p class="text-xs text-gray-500">
            Membantu UMKM, sekolah, perusahaan, dan startup bertransformasi
            secara digital sejak 2026.
          </p>
        </div>

        <!-- SERVICES -->
        <div>
          <h4 class="text-white font-semibold mb-3">Layanan</h4>
          <ul class="space-y-2 text-sm">
            <li><NuxtLink to="/service-details/company-profile" class="footer-link">Company Profile</NuxtLink></li>
            <li><NuxtLink to="/service-details/web-application" class="footer-link">Web Application</NuxtLink></li>
            <li><NuxtLink to="/service-details/mobile-application" class="footer-link">Mobile Application</NuxtLink></li>
            <li><NuxtLink to="/service-details/uiux-design" class="footer-link">UI / UX Design</NuxtLink></li>
            <li><NuxtLink to="/service-details/maintenance-support" class="footer-link">Maintenance & Support</NuxtLink></li>
          </ul>
        </div>

        <!-- MENU -->
        <div>
          <h4 class="text-white font-semibold mb-3">Menu</h4>
          <ul class="space-y-2 text-sm">
            <li><NuxtLink to="/" class="footer-link">Home</NuxtLink></li>
            <li><NuxtLink to="/services" class="footer-link">Services</NuxtLink></li>
            <li><NuxtLink to="/pricing" class="footer-link">Pricing</NuxtLink></li>
            <li><NuxtLink to="/portfolio" class="footer-link">Portfolio</NuxtLink></li>
            <li><NuxtLink to="/about" class="footer-link">About</NuxtLink></li>
            <li><NuxtLink to="/contact" class="footer-link">Contact</NuxtLink></li>
          </ul>
        </div>

        <!-- CONTACT -->
        <div>
          <h4 class="text-white font-semibold mb-3">Kontak</h4>
          <p class="text-sm mb-2">
            WhatsApp:<br />
            <a href="https://wa.me/6282123925828" target="_blank" class="footer-link">
              +62 821 2392 5828
            </a>
          </p>
          <p class="text-sm">
            Email:<br />
            <a href="mailto:elzeetechnology@gmail.com" class="footer-link">
              elzeetechnology@gmail.com
            </a>
          </p>
        </div>
      </div>

      <!-- BOTTOM BAR -->
      <div class="border-t border-gray-800">
        <div
          class="max-w-7xl mx-auto px-6 py-4
                 flex flex-col md:flex-row
                 items-center justify-between
                 text-xs text-gray-500 gap-2"
        >
          <span>© 2026 ELZEE Technology. All rights reserved.</span>
          <span>Crafted with ❤️ using modern web technologies</span>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.nav-link {
  @apply text-gray-700 hover:text-black transition;
}

.router-link-active {
  @apply text-black font-semibold;
}

.dropdown-link {
  @apply block px-6 py-3
    text-gray-700 hover:bg-gray-50 hover:text-black transition;
}

.footer-link {
  @apply text-gray-400 hover:text-white transition;
}

.footer-link.router-link-active {
  @apply text-white font-semibold;
}

/* MOBILE */
.mobile-link {
  @apply block py-2 text-gray-800 font-medium;
}

.mobile-sub {
  @apply block py-1 text-gray-600 text-sm;
}

/* ANIMATION */
.slide-enter-active,
.slide-leave-active {
  transition: all 0.25s ease;
}

.slide-enter-from,
.slide-leave-to {
  opacity: 0;
  transform: translateY(-10px);
}
</style>

