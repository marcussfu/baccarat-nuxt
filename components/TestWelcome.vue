<template>
  <div class="bg-white py-24">
    <div class="flex flex-col items-center">
      <h1 class="text-6xl font-semibold text-blue-600">Hello World</h1>
      <p class="mt-4 text-9xl font-bold text-gray-900">{{ title }}</p>
    </div>
    <!-- <NuxtWelcome /> -->
  </div>
</template>

<script lang="ts" setup>
const year = 2023
const title = `${year} testaa`
</script>
