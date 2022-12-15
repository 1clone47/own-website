<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header
    class="bg-zinc-500 flex flex-row h-20 items-center space-x-4 text-white font-mono"
  >
    <div class="flex flex-row mt-5">
      <div class="flex flex-col px-4 ml-32 pointer-events-none">
        <p class="text-white text-3xl">Andy Wagner</p>
        <p class="text-white text-lg">Azubi / Entwicklung</p>
      </div>
      <div class="flex flex-row space-x-8 ml-48">
        <RouterLink to="/">
          <p class="text-lg mt-9">Home</p>
        </RouterLink>
        <RouterLink to="/resume">
          <p class="text-lg mt-9">Resume</p>
        </RouterLink>
        <RouterLink to="/projects">
          <p class="text-lg mt-9">Projects</p>
        </RouterLink>
        <RouterLink to="/contact">
          <p class="text-lg mt-9">Kontakt</p>
        </RouterLink>
      </div>
    </div>
  </header>
  <body>
    <RouterView />
  </body>
</template>
