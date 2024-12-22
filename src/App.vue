<script setup lang="ts">
import { Carousel } from "@swarmakit/vue";

const slides = [
  { src: "/img1.jpg", alt: "Image 1" },
  { src: "/img3.jpg", alt: "Image 2" },
  { src: "/img3.jpg", alt: "Image 2" },
];

const carouselInterval = 5000;
</script>

<template>
  <div>
    <Carousel :slides="slides" :interval="carouselInterval" />
  </div>
</template>

<style scoped></style>
