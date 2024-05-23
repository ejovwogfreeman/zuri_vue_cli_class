<script setup>
  // import { RouterLink } from "vue-router";
  import Navbar from "./components/Navbar.vue";
  import Footer from "./components/Footer.vue";
</script>

<template>
  <Navbar title="Click Me" color="red" />
  <RouterView />
  <Footer />
</template>
