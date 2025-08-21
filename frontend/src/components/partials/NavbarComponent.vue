<template>
  <nav>
    <RouterLink to="/" class="router-link-exact-active">Home</RouterLink>
    <RouterLink to="/about" class="router-link-exact-active">About</RouterLink>
    <RouterLink to="/contact" class="router-link-exact-active">Contact</RouterLink>
  </nav>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
