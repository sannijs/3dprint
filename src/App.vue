<template>
  <div class="app">
    <Navbar />
    <Hero />
    <Services />
    <Upload3D />
    <Pricing />
    <Contact />
    <FooterSection />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Services from './components/Services.vue'
import Upload3D from './components/Upload3D.vue'
import Pricing from './components/Pricing.vue'
import Contact from './components/Contact.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
}
</style>
