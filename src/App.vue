<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="bg-gray-800 text-white py-4">
    <nav class="container mx-auto flex justify-between items-center px-4">
      <RouterLink
        to="/"
        class="text-xl font-semibold hover:text-gray-300 mx-auto"
        >Home</RouterLink
      >
    </nav>
  </header>

  <RouterView />
</template>
