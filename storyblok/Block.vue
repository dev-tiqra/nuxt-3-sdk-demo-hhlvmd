<template>
  <div v-editable="blok" class="flex py-8 mb-6" :class="blok.css">
    <div v-for="blok in blok.body" :key="blok._uid">
      <StoryblokComponent :blok="blok" />
    </div>
  </div>
</template>

<script setup>
defineProps({ blok: Object });
</script>
