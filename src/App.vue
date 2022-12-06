<script setup>
import { RouterLink, RouterView } from 'vue-router';
import NavigationVue from './components/Navigation.vue';
import FooterVue from './components/Footer.vue';
</script>

<template>
  <NavigationVue />

  <RouterView />

  <FooterVue />
</template>
