<script setup>
import CategorySelect from '../components/CategorySelect.vue'
</script>


<template>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recommended songs
    </button>
    <div class="py-1.5"></div>
    <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/30/300/300"/>
      <CategorySelect category="Music" image="https://picsum.photos/id/40/300/300"/>
      <CategorySelect category="Live ivent" image="https://picsum.photos/id/45/300/300"/>
      <CategorySelect category="K-POP" image="https://picsum.photos/id/46/300/300"/>
      <CategorySelect category="HIPHOP" image="https://picsum.photos/id/47/300/300"/>
      <CategorySelect category="Made For You" image="https://picsum.photos/id/31/300/300"/>
      <CategorySelect category="New Releases" image="https://picsum.photos/id/32/300/300"/>
      <CategorySelect category="Merch" image="https://picsum.photos/id/33/300/300"/>
      <CategorySelect category="J-Tracks" image="https://picsum.photos/id/34/300/300"/>
      <CategorySelect category="Radio Shows" image="https://picsum.photos/id/35/300/300"/>
      <CategorySelect category="Audiobooks" image="https://picsum.photos/id/36/300/300"/>
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/37/300/300"/>
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/38/300/300"/>
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/39/300/300"/>
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/48/300/300"/>
    </div> 
  </div>
</template>

