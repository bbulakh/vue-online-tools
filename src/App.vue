<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import HeroMain from './components/HeroMain.vue'
import ToolsSection from './components/ToolsSection.vue'
import FooterMain from './components/FooterMain.vue'
</script>

<template>
  <NavBar />
  <header>
    <div class="wrapper">
      <HeroMain />

      <nav class="justify-center gap-3 hidden">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <ToolsSection />

  <div class="hidden"><RouterView /></div>
  <FooterMain />
</template>


