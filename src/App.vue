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
  <div class="carousel-container">
    <h2>Product Showcase</h2>
    <Carousel :slides="slides" :interval="carouselInterval" />
  </div>
</template>

<style scoped>
.carousel-container {
  display: flex;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h2 {
  font-size: 24px;
  text-align: center;
  margin-bottom: 20px;
}
</style>
