<template>
  <div v-editable="blok" class="py-2" data-test="feature">
    <div>{{ blok.content }}</div>
  </div>
</template>

<script setup>
defineProps({ blok: Object });
</script>
