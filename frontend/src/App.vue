<script setup>
import FooterSection from "./components/FooterSection.vue";
import NavbarLandingPage from "./components/NavbarLandingPage.vue";
</script>

<template>
  <div class="font-sans text-gray-800">
    <!-- <NavbarLandingPage /> -->
    <RouterView />
    <!-- <FooterSection /> -->
  </div>
</template>

<style scoped>
div {
  overflow-x: hidden;
}
</style>
