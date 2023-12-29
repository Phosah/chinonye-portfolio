<template>
  <nav class="flex justify-between bg-red-300">
    <ul class="flex space-x-6">
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
      <li>Behance</li>
      <li>Resume</li>
    </ul>
    <p>Hire me</p>
  </nav>

  <header class="flex items-center justify-between py-4">
    <div>
      <p>Hi there!</p>
      <p>I am Chinonye Umeh, a product designer based in Lagos, Nigeria.</p>
    </div>

    <div>
      <img :src="Chinonye" alt="Chinonye" class="h-72" />
    </div>
  </header>
</template>

<script setup>
import Chinonye from "@/assets/chinonye.png";
</script>
