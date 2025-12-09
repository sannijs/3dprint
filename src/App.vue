<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400..900&display=swap" rel="stylesheet">
  <div class="app">
    <Navbar />
    <Hero />
    <Upload3D />
    <Pricing />
    <Contact />
    <FooterSection />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Upload3D from './components/Upload3D.vue'
import Pricing from './components/Pricing.vue'
import Contact from './components/Contact.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<style>
body {
  margin-left: 5%;
  margin-left: 5%;
  font-family: Arial, sans-serif;
  background: #000000;
  font-family: orbitron, Avenir, Helvetica, Arial, sans-serif;
}
</style>
