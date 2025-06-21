<template>
  <div class="bg-[#1A1A1A] text-white  flex justify-center w-full py-[64px]">
    <div class="adjara-container">


      <div class="w-full flex justify-between items-center mb-[64px]">

        <div class="flex gap-3">
          <span class="inline-block w-1.5 h-7 bg-adjara-yellow"></span>
          <h2 class="text-xl flex items-center gap-2 font-adjara-mt leading-9">{{ title }}</h2>
        </div>
        <div class="flex gap-[12px]">
          <span
            class="rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300 cursor-pointer">ყველა</span>
          <span
            class="rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300 cursor-pointer">გადაცემები</span>
          <span
            class="active [&.active]:bg-[#808080] rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300 cursor-pointer">დოკუმენტური</span>
          <span
            class="rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300 cursor-pointer">საბავშვო</span>
          <span
            class="rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300 cursor-pointer">ლაივი</span>
        </div>
        <a
          :href="more?.link"
          class="bg-[#FFC038] text-black text-sm font-semibold px-[16px] py-[8px] rounded-[6px] hover:bg-[#ff7e38] transition-all duration-300">
            {{ more?.title }}
        </a>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-[32px]">

        <template v-if="videos.length">
          <div v-for="video in videos" :key="video.date" class="bg-[#1A1A1A] rounded overflow-hidden">
            <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
              <img :src="video?.image" alt="" class="w-full h-full object-cover rounded-lg " />
              <div class="absolute inset-0 flex items-center justify-center  ">
                <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
                  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd"
                    d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z"
                    fill="white" />
                </svg>
              </div>
            </div>
            <div class="pt-[16px]">
              <h3 class="text-[#f3b933] font-semibold text-sm mb-3">{{ video?.category }}</h3>
              <p
                class="text-[#808080] font-ajaratv text-xs font-normal not-italic leading-[normal] tracking-[0.045em] mb-3">
                {{ video?.date }}
              </p>
              <p class="text-grayText font-ajaratv text-xs font-normal not-italic leading-normal tracking-wide72">
                {{ video?.title }}
              </p>
            </div>
          </div>
        </template>

      </div>
    </div>
  </div>
</template>

<script setup>

defineProps({
  videos: {
    type: Array,
    default: () => []
  },
  title: {
    type: String,
    default: () => ""
  },
  more: {
    type: Object,
    default: () => {}
  }
})

</script>