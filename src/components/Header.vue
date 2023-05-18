<script setup>
import { reactive } from "vue";

const word = reactive({
  header: "Helloooo Semuaa",
  body: "My name is Putri milenium dion, in next section i will show my portfolio and my interest",
});
</script>

<template>
  <div>
    <div
      class="hero min-h-screen"
      style="background-image: url(src/assets/coba.jpeg)"
    >
      <div class="hero-overlay bg-opacity-60"></div>
      <div class="hero-content text-center text-neutral-content text-white">
        <div class="max-w-md">
          <h1 class="mb-5 text-5xl font-bold">{{ word.header }}</h1>
          <p class="mb-5">
            {{ word.body }}
          </p>
          <a href="#introduction">
            <button class="btn btn-primary">Get Started</button>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>