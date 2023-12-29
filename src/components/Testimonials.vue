<template>
  <section class="bg-red-300 py-4">
    <h2 class="mb-2">Testimonials</h2>

    <section class="flex space-x-4">
      <div class="p-3 border border-blue-200 rounded-md">
        <component
          :is="QuotationMarksIcon"
          class="w-12 h-12 shrink-0 text-white"
          aria-hidden="true"
        ></component>

        <p class="mb-4">
          I had the pleasure of working closely with Chinonye on the Savebud
          project, and I couldn't have asked for a better team-lead. Chinonye is
          a true creative visionary with an unparalleled passion for design. Her
          attention to detail, innovative ideas, and dedication to user-centric
          solutions were nothing short of inspiring. I'll recommend working with
          her anytime
        </p>

        <p>- Precious Abachukwu</p>
        <p>Product Designer</p>
      </div>

      <div class="p-3 border border-blue-200 rounded-md">
        <component
          :is="QuotationMarksIcon"
          class="w-12 h-12 shrink-0 text-white"
          aria-hidden="true"
        ></component>

        <p class="mb-4">
          I had the pleasure of working closely with Chinonye on the Savebud
          project, and I couldn't have asked for a better team-lead. Chinonye is
          a true creative visionary with an unparalleled passion for design. Her
          attention to detail, innovative ideas, and dedication to user-centric
          solutions were nothing short of inspiring. I'll recommend working with
          her anytime
        </p>

        <p>- Precious Abachukwu</p>
        <p>Product Designer</p>
      </div>
    </section>
  </section>
</template>

<script setup>
import QuotationMarksIcon from "./icons/QuotationMarksIcon.vue";
</script>
