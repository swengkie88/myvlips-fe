<script setup>
defineProps({
  title: {
    type: String,
    default: 'Ini fitur vlips'
  }
})
</script>

<template>
  <div class="bg-white rounded">
    <div class="p-8">
      <h3 class="heading3-blue">
        {{ title }}
      </h3>
      <p class="text-slate-700">
        <slot />
      </p>
    </div>
  </div>
</template>
