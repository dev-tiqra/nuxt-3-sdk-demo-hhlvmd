<template>
  <div v-editable="blok" class="py-2" data-test="link">
    <h1 class="text-lg">{{ blok.copyright }}</h1>
  </div>
</template>

<script setup>
defineProps({ blok: Object });
</script>
