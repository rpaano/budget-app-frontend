<template>
  <div class="flex flex-col sm:flex-row sm:h-screen">
    <div class="w-full sm:w-6/12 lg:5/12 p-6 bg-white">
      <NuxtPage />
    </div>
    <div
      class="
        w-full
        sm:w-6/12
        lg:7/12
        bg-gradient-to-tr
        from-primary-500
        to-primary-400
        flex
        items-center
        justify-center
        p-6
      "
    >
    </div>
  </div>
</template>
<script setup lang="ts">
  // import './assets/css/tailwind.css'
  const layout = "custom";
</script>