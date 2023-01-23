<script lang="ts" setup>
import ImageModal from "./ImageModal.vue";

</script>

<template>
  <div class="bg-secondary">
    <h2 class="text-3xl font-bold mb-12 pb-4 text-center">Photography</h2>
    <div class="gallery flex flex-wrap justify-center shadow-lg filmstrip">
      <ImageModal imagelink="./assets/images/buddy.jpg" iname="buddy" />
      <ImageModal imagelink="./assets/images/turtle.jpg" iname="turtle" />
      <ImageModal imagelink="./assets/images/sl-wls.jpg" iname="owls" />
      <ImageModal imagelink="./assets/images/beach.png" iname="beach" />
    </div>
  </div>
</template>

<style scoped>
.filmstrip {
  --background: rgba(0, 0, 0, 0.35);
  --size: 10px;
  background-image: linear-gradient(
      to right,
      var(--background) var(--size),
      transparent var(--size)
    ),
    linear-gradient(
      to bottom,
      var(--background) var(--size),
      transparent var(--size)
    ),
    linear-gradient(
      to right,
      var(--background) var(--size),
      transparent var(--size)
    ),
    linear-gradient(
      to bottom,
      var(--background) var(--size),
      transparent var(--size)
    ),
    linear-gradient(
      to bottom,
      transparent var(--size),
      var(--background) var(--size)
    );
  background-size: calc(var(--size) * 2) var(--size),
    calc(var(--size) * 2) var(--size), calc(var(--size) * 2) var(--size),
    calc(var(--size) * 2) var(--size), 100% calc(100% - var(--size) * 3);
  background-repeat: repeat-x;
  background-position: 0 var(--size), top left, 0 calc(100% - var(--size)),
    bottom left, 0 var(--size);
  padding: calc(var(--size) * 3) calc(var(--size) * 2.5);
  box-sizing: border-box;
}
</style>
