<script setup>
import { toRefs } from 'vue';
import { RouterLink } from 'vue-router';

const props = defineProps({
    image: String,
    title: String,
    subTitle: String,
});
const { image, title, subTitle } = toRefs(props);
</script>


<template>
    <div>
      <RouterLink to="library">
        <div class="bg-[#111111] p-4 rounded-md m-2 hover:bg-[#252525] cursor-pointer">
          <img class="rounded-md" :src="image" />
          <div class="text-white text-[17px] font-semibold pt-4">{{ title }}</div>
          <div class="text-gray-400 text-[14px] pt-1 pb-3">{{ subTitle }}</div>
        </div>
      </RouterLink>
    </div>
</template>

