<template>
  <nav class="flex items-center justify-between mb-3">
    <ul class="flex space-x-6 text-black-300 cursor-pointer">
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
      <li>Behance</li>
      <li>Resume</li>
    </ul>
    <p
      class="w-48 px-4 py-2 text-center bg-black-200 text-white-100 rounded-md cursor-pointer"
    >
      Hire me
    </p>
  </nav>

  <header
    class="flex items-center justify-between mb-20 py-6 px-4 bg-blue-100 rounded-md"
  >
    <div class="w-2/3 pr-12 text-3xl">
      <p class="mb-4">Hi there!</p>
      <p>I am Chinonye Umeh, a product designer based in Lagos, Nigeria.</p>
    </div>

    <div class="transform translate-y-28">
      <img :src="Chinonye" alt="Chinonye" class="h-72" />
    </div>
  </header>
</template>

<script setup>
import Chinonye from "@/assets/chinonye.png";
</script>
