<script setup lang="ts">
import TheNavigation from '../components/TheNavigation.vue'
import { RouterView } from 'vue-router'
</script>

<template>
  <TheNavigation />
  <main>
    <RouterView />
  </main>
</template>
