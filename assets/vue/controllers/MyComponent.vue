<template>
  <div>I'm a {{ name }}!</div>
</template>

<script setup>
  defineProps({
    name: String
  });
</script>