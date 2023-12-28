<template>
  <div class="mb-8">
    <div class="mb-2">
      <img :src="project.img" :alt="project.alt" />
    </div>

    <p>
      <span>{{ project.title }}</span> - {{ project.subtitle }}
    </p>
    <p>
      {{ project.text }}
    </p>

    <div class="flex space-x-6 my-2">
      <div
        v-for="(tag, ix) in project.tags"
        :key="ix"
        class="px-3 py-1 bg-green-200 rounded-md"
      >
        {{ tag }}
      </div>
    </div>

    <div class="flex items-center space-x-2">
      <p>View case study</p>
      <component
        :is="RightArrowIcon"
        class="w-4 h-4 shrink-0 text-white"
        aria-hidden="true"
      ></component>
    </div>
  </div>
</template>

<script setup>
import WorkPerk from "@/assets/workperk.png";
import RightArrowIcon from "./icons/RightArrowIcon.vue";

defineProps({
  project: {
    type: Object,
    required: true,
  },
});
</script>
