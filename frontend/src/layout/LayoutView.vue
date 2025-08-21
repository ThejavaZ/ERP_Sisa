<template>
  <HeaderComponent />
  <main>
    <RouterView />
  </main>
  <FooterComponent />
</template>

<script setup lang="ts">
import HeaderComponent from '@/components/partials/HeaderComponent.vue'
import FooterComponent from '@/components/partials/FooterComponent.vue'
import { RouterView } from 'vue-router'
</script>
