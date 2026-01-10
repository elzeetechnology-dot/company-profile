<template>
  <!-- HERO -->
  <section class="bg-gradient-to-b from-gray-50 to-white">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <span
        class="inline-block mb-4 px-4 py-1 text-sm font-medium
               text-blue-600 bg-blue-50 rounded-full"
      >
        Hubungi Kami
      </span>

      <h1 class="text-4xl md:text-5xl font-bold mb-6">
        Mari Diskusikan Kebutuhan Digital Anda
      </h1>

      <p class="text-gray-600 max-w-2xl mx-auto text-lg">
        Kami siap membantu Anda membangun website, aplikasi,
        dan sistem digital yang profesional dan scalable.
      </p>
    </div>
  </section>

  <!-- CONTACT CONTENT -->
  <section
    class="max-w-7xl mx-auto px-6 py-20
           grid md:grid-cols-2 gap-14 items-start"
  >
    <!-- CONTACT INFO -->
    <div>
      <h2 class="text-2xl font-semibold mb-6">
        Informasi Kontak
      </h2>

      <p class="text-gray-600 mb-8 leading-relaxed">
        Jangan ragu untuk menghubungi kami.
        Konsultasi awal gratis untuk membantu Anda
        menemukan solusi digital terbaik.
      </p>

      <ul class="space-y-5 text-gray-700">
        <li class="flex items-start gap-3">
          <span class="font-medium">Email</span>
          <a
            href="mailto:elzeetechnology@gmail.com"
            class="text-blue-600 hover:underline"
          >
            elzeetechnology@gmail.com
          </a>
        </li>

        <li class="flex items-start gap-3">
          <span class="font-medium">WhatsApp</span>
          <a
            href="https://wa.me/6282123925828"
            target="_blank"
            class="text-blue-600 hover:underline"
          >
            +62 821-2392-5828
          </a>
        </li>

        <li class="flex items-start gap-3">
          <span class="font-medium">Jam Operasional</span>
          <span>Senin – Jumat, 09.00 – 17.00</span>
        </li>
      </ul>

      <div class="mt-10">
        <a
          href="https://wa.me/6282123925828"
          target="_blank"
          class="inline-flex items-center gap-2
                 bg-black text-white px-8 py-4
                 rounded-xl font-semibold
                 hover:bg-gray-800 transition"
        >
          Konsultasi via WhatsApp
          →
        </a>
      </div>
    </div>

    <!-- CONTACT FORM -->
    <div class="bg-white rounded-3xl shadow-md p-10">
      <h2 class="text-2xl font-semibold mb-2">
        Kirim Pesan
      </h2>
      <p class="text-gray-600 mb-8 text-sm">
        Isi form di bawah ini dan kami akan menghubungi Anda
        secepat mungkin.
      </p>

      <form class="space-y-6">
        <div>
          <label class="block text-sm font-medium mb-2">
            Nama
          </label>
          <input
            type="text"
            placeholder="Nama lengkap"
            class="w-full border rounded-xl px-4 py-3
                   focus:outline-none focus:ring-2 focus:ring-black"
          />
        </div>

        <div>
          <label class="block text-sm font-medium mb-2">
            Email
          </label>
          <input
            type="email"
            placeholder="Alamat email"
            class="w-full border rounded-xl px-4 py-3
                   focus:outline-none focus:ring-2 focus:ring-black"
          />
        </div>

        <div>
          <label class="block text-sm font-medium mb-2">
            Pesan
          </label>
          <textarea
            rows="4"
            placeholder="Ceritakan kebutuhan Anda..."
            class="w-full border rounded-xl px-4 py-3
                   focus:outline-none focus:ring-2 focus:ring-black"
          ></textarea>
        </div>

        <button
          type="button"
          class="w-full bg-black text-white py-4
                 rounded-xl font-semibold
                 hover:bg-gray-800 transition"
        >
          Kirim Pesan
        </button>
      </form>
    </div>
  </section>
</template>
