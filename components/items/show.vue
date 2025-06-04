<template>
  <a :href="permalink" class="w-full flex flex-col justify-center items-start gap-[24px] ">
    <img 
      :src="thumbnail"
      class="w-full aspect-280/188 object-cover rounded transition duration-300 hover:scale-110 " alt="show1" />
    <div>
      <h3 class="text-[16px] text-[#000000] font-semibold mb-[4px]">{{ title }}</h3>
      <p class="text-[14px] text-[#808080]">{{ desc }}</p>
    </div>
  </a>
</template>
<script setup lang="ts">
defineProps({
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
  }
})

</script>