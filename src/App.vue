<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <div class="absolute top-0 left-0 w-full bg-white">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/score">Marcador</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
</style>
