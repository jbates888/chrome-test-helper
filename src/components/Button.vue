<script setup>
defineProps({
  text: {
    type: String,
    required: true
  },
  color: {
    type: String,
    required: true
  }
})
</script>

<template>
    <button class="btn">{{ text }}</button>
</template>