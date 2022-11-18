<script setup>
defineProps({
  type: {
    type: String,
    default: 'submit'
  }
})
</script>

<template>
  <button
    :type="type"
    class="inline-flex items-center px-4 py-2 bg-[#2E8AE6] border border-transparent rounded-md font-medium text-white tracking-widest hover:bg-gray-700 active:bg-gray-900 focus:outline-none focus:border-gray-900 focus:ring focus:ring-gray-300 disabled:opacity-25 transition"
  >
    <slot />
  </button>
</template>
