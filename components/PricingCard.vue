<template>
  <div
    class="relative rounded-3xl p-8 bg-white border border-black/5
           transition-all duration-300 ease-out
           hover:-translate-y-3 hover:shadow-2xl"
    :class="highlight
      ? 'ring-2 ring-black scale-[1.02]'
      : 'hover:ring-1 hover:ring-black/10'"
  >
    <!-- BADGE -->
    <div
      v-if="highlight"
      class="absolute -top-4 left-1/2 -translate-x-1/2
             bg-black text-white text-xs font-semibold
             px-4 py-1 rounded-full shadow"
    >
      Most Popular
    </div>

    <!-- TITLE -->
    <h3 class="text-xl font-bold mb-2">
      {{ title }}
    </h3>

    <!-- DESCRIPTION -->
    <p class="text-sm text-gray-600 mb-6">
      {{ desc }}
    </p>

    <!-- PRICE -->
    <div class="mb-6">
      <span
        v-if="price !== 'Custom'"
        class="text-3xl font-bold"
      >
        Rp {{ formattedPrice }}
      </span>

      <span
        v-else
        class="text-3xl font-bold"
      >
        Custom
      </span>

      <span
        v-if="price !== 'Custom'"
        class="text-sm text-gray-500 ml-1"
      >
        / project
      </span>
    </div>

    <!-- FEATURES -->
    <ul class="space-y-3 mb-8">
      <li
        v-for="(feature, index) in features"
        :key="index"
        class="flex items-start gap-3 text-sm text-gray-700"
      >
        <span
          class="mt-1 flex-shrink-0 w-4 h-4 rounded-full
                 bg-black text-white text-xs
                 flex items-center justify-center"
        >
          ✓
        </span>
        <span>{{ feature }}</span>
      </li>
    </ul>

    <!-- CTA -->
    <NuxtLink
      to="/contact"
      class="block text-center rounded-xl py-3 font-semibold
             transition"
      :class="highlight
        ? 'bg-black text-white hover:bg-gray-800'
        : 'border border-black text-black hover:bg-black hover:text-white'"
    >
      Pilih Paket
    </NuxtLink>
  </div>
</template>

<script setup>
import { computed } from 'vue'

const props = defineProps({
  title: {
    type: String,
    required: true,
  },
  price: {
    type: String,
    required: true,
  },
  desc: {
    type: String,
    required: true,
  },
  features: {
    type: Array,
    required: true,
  },
  highlight: {
    type: Boolean,
    default: false,
  },
})

const formattedPrice = computed(() => {
  if (props.price === 'Custom') return ''
  return props.price.replace(/\B(?=(\d{3})+(?!\d))/g, '.')
})
</script>
