<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Greet from "./components/Greet.vue";
</script>

<template>
  <div class="container">
    <h1>Welcome to Tauri!</h1>

    <Suspense>
    <Greet />
    </Suspense>
  </div>
</template>

