<template>
  <div class="bg-yellow-300 py-4">
    <h2>Featured Projects</h2>
    <div v-for="(project, ix) in projects" :key="ix">
      <ProjectLayout :project="project" />
    </div>
  </div>
</template>

<script setup>
import ProjectLayout from "./ProjectLayout.vue";
import WorkPerk from "@/assets/workperk.png";
import SaveBud from "@/assets/savebud.png";

const projects = [
  {
    id: 1,
    title: "WORKPERK ",
    subtitle: "Free Lunch App",
    text: "WorkPerk offers a streamlined and user-friendly solution to address the issue of employee motivation and engagement.",
    tags: ["UI/UX", "workplace", "free lunch", "case study"],
    img: WorkPerk,
    alt: "WorkPerk",
  },
  {
    id: 2,
    title: "SAVEBUD",
    subtitle: "A Gamified Savings and Budgeting App",
    text: "SaveBud is a gamified savings and budgeting platform that transforms financial management into an engaging and rewarding experience",
    tags: ["UI/UX", "savings", "budgeting", "gamification"],
    img: SaveBud,
    alt: "WorkPerk",
  },
];
</script>
