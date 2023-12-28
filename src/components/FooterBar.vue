<template>
  <div class="flex justify-between bg-yellow-300 py-4">
    <div class="flex space-x-4">
      <div class="inline-block p-2 bg-red-50 rounded-full">
        <img :src="Instagram" alt="Instagram" class="h-4 w-4" />
      </div>
      <div class="inline-block p-2 bg-red-50 rounded-full">
        <img :src="X" alt="X" class="h-4 w-4" />
      </div>
      <div class="inline-block p-2 bg-red-50 rounded-full">
        <img :src="Behance" alt="Behance" class="h-4 w-4" />
      </div>
      <div class="inline-block p-2 bg-red-50 rounded-full">
        <img :src="LinkedIn" alt="LinkedIn" class="h-4 w-4" />
      </div>
      <div class="inline-block p-2 bg-red-50 rounded-full">
        <img :src="Gmail" alt="Gmail" class="h-4 w-4" />
      </div>
    </div>
    <p>Chinonye Umeh, 2023</p>

    <!-- This two components are different icons but show only the same Gmail icon. To fix -->
    <!-- <div>
      <component
        :key="GmailIcon"
        :is="GmailIcon"
        class="w-12 h-12 shrink-0 text-white"
        aria-hidden="true"
      ></component>
    </div> -->

    <!-- <div>
      <component
        :is="LinkedInIcon"
        class="w-12 h-12 shrink-0 text-white"
        aria-hidden="true"
      ></component>
    </div> -->
  </div>
</template>

<script setup>
import Behance from "@/assets/behance.png";
import Gmail from "@/assets/gmail.png";
import Instagram from "@/assets/instagram.png";
import LinkedIn from "@/assets/linkedIn.png";
import X from "@/assets/x.png";

import LinkedInIcon from "./icons/LinkedInIcon.vue";
import GmailIcon from "./icons/GmailIcon.vue";
</script>
