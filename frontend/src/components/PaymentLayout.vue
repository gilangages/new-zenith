<script setup>
import { RouterView } from "vue-router";
import FooterSection from "./FooterSection.vue";
import NavbarUser from "./NavbarUser.vue";
</script>

<template>
  <div class="min-h-screen flex flex-col bg-white">
    <!-- NAVBAR -->
    <NavbarUser />

    <!-- MAIN CONTENT -->
    <main class="flex-1 w-full">
      <RouterView />
    </main>

    <FooterSection />
  </div>
</template>

<style scoped>
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css";
</style>
