<script setup>
import background from './assets/grass.jpg'
import logo from './assets/logo.png'

</script>

<template>
  <div class="h-screen bg-cover bg-no-repeat bg-center" :style="{ backgroundImage: `url(${background})` }">
    <div class="flex flex-col items-center justify-center h-full">
      <img :src="logo" alt="Minecraft NZ Logo" />
    </div>
  </div>
</template>

