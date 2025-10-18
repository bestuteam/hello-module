<template>
  <div class="p-6 text-center">
    <h1 class="text-3xl font-bold mb-4 text-primary">
      👋 Hello from the external module!
    </h1>
    <p class="text-lg">
      This component was loaded dynamically from an external GitHub repository.
    </p>
  </div>
</template>

<script setup lang="ts">
console.log("✅ HelloModule.vue loaded successfully!");
</script>

<style scoped>
.text-primary {
  color: #42b883;
}
</style>
