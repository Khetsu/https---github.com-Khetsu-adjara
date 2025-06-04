<template>
  <div class="">
    <a href="#" class="flex flex-col w-full gap-[12px] ">
      <div v-if="thumbnail" class="rounded aspect-105/68 overflow-hidden">
        <img :src="thumbnail" class="w-full h-full object-cover transition duration-300 hover:scale-110" />
      </div>
      <p class="text-xs text-adjara-gray font-adjara-nu">{{ date }}</p>
      <h3 class="text-sm font-adjara-mt leading-tight">
        {{ title }}
      </h3>
      <p :class="`text-xs text-adjara-gray font-adjara-nu line-clamp-${clamp}`">
        {{ desc }}
      </p>
    </a>
  </div>
</template>
<script setup lang="ts">
defineProps({
  date: {
    type: Date,
    default: ""
  },
  title: {
    type: String,
    default: "",
  },
  desc: {
    type: String,
    default: "",
  },
  thumbnail: {
    type: String,
    default: "",
  },
  permalink: {
    type: String,
    default: "",
  },
  clamp: {
    type: Number,
    default: 3
  }
})
</script>