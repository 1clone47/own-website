<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="flex flex-row bg-stone-800 h-10 items-center space-x-4">
    <div class="flex flex-row">
      <p class="text-white ml-4 text-lg">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-6 h-6"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
          />
        </svg>
      </p>
      <p class="text-lg text-white px-4 items-center">1clone47</p>
    </div>
  </header>
  <RouterView />
</template>
