<template>
  <header>
    <img src="/src/assets/logo.png" alt="logo" v-bind:width="150" />

    <NavbarComponent />
  </header>
</template>

<script setup lang="ts">
import NavbarComponent from './NavbarComponent.vue'
</script>
