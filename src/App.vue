<script setup>
import background from "./assets/grass.jpg";
import logo from "./assets/logo.png";
</script>

<template>
  <div
    class="h-screen bg-cover bg-no-repeat bg-center"
    :style="{ backgroundImage: `url(${background})` }"
  >
    <div class="flex flex-col items-center justify-center h-full">
      <img :src="logo" alt="Minecraft NZ Logo" />
      <div
        class="mt-6 flex max-w-md flex-col items-center rounded bg-stone-900/60 px-6 py-5 text-center backdrop-blur"
      >
        <p class="text-sm text-stone-200">
          Explore the history of NZ's first Minecraft community:<br />world
          downloads, interactive maps, screenshots, and more.
        </p>
        <a
          href="https://archive.minecraft.co.nz"
          class="mt-4 rounded bg-emerald-600 px-6 py-3 text-lg font-semibold text-white transition hover:bg-emerald-500"
          >Visit the Archive</a
        >
      </div>
    </div>
  </div>
</template>
