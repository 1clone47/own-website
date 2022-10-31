<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="flex flex-row bg-stone-800 h-12 items-center space-x-4">
    <div class="flex flex-row">
      <RouterLink to="/">
        <img
          src="./assets/images/no-background.png"
          class="h-8 w-8 ml-4"
          alt=""
        />
      </RouterLink>
      <RouterLink to="/me">
        <p class="text-lg text-white px-4 items-center">1clone47.de</p>
      </RouterLink>
    </div>
  </header>
  <RouterView />
</template>
