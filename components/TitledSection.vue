<template>
  <div class="bg-[#F7F7F7] w-full py-[64px] px-4 lg:px-0">
    <div class="bg-[#F7F7F7] max-w-[1220px] w-full mx-auto py-[48px]">

      <div class="flex justify-between items-center mb-8">
        <div class="flex gap-3">
          <span class="inline-block w-[6px] h-[28px]  bg-adjara-yellow " />
          <h2 v-if="title" class="text-xl flex items-center gap-2 font-adjara-mt leading-9">
            {{ title }}
          </h2>
        </div>
        <div class="flex gap-3">
          <a v-if="permalink?.url" :href="permalink?.url"
            class="bg-[#F2F2F2] text-black text-sm font-medium px-[16px] py-[8px] rounded  hover:bg-[#D9D9D9] transition-all duraction-300 ">
            {{ permalink?.title }}
          </a>
          <template v-if="hasArrow">
            <button
              class="bg-[#F2F2F2] w-[36px] h-[36px] cursor-pointer rounded flex items-center justify-center text-black hover:bg-[#D9D9D9] transition-all duraction-300">
              <img src="../public/icons/arrow_left_icon.svg" alt="arrow_left" class=" " />
            </button>
            <button
              class="bg-[#F2F2F2] w-[36px] h-[36px] cursor-pointer rounded flex items-center justify-center text-black hover:bg-[#D9D9D9] transition-all duraction-300">
              <img src="../public/icons/arrow_right_icon.svg" alt="arrow_left" class=" " />
            </button>
          </template>
        </div>
      </div>
      <slot />

    </div>
  </div>
</template>
<script setup lang="ts">
interface BunttonPermalink {
  url: string
  title: string
}

interface TitledSection {
  permalink: BunttonPermalink
  hasArrow: boolean
  title: boolean | string
}

defineProps<TitledSection>()
</script>
