<template>
  <div v-editable="blok" class="py-2">
    <div class="flex justify-center">
      <a :href="blok.link.url" :target="blok.link.target">
        <img
          :src="blok.icon.filename"
          :alt="blok.icon.alt"
          width="32"
          height="32"
        />
      </a>
    </div>
  </div>
</template>

<script setup>
defineProps({ blok: Object });
</script>
