<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="text-green-800 bg-green-100/[7] font-semibold">{{ msg }}</h1>
  </div>
</template>
