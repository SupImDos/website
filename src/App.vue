<script setup>
import About from './components/About.vue'
import Hero from './components/Hero.vue'
import NavBar from './components/NavBar.vue'
import Pets from './components/Pets.vue'
import Portfolio from './components/Portfolio.vue'
import Skills from './components/Skills.vue'
</script>

<template>
  <main class="bg-white dark:bg-gray-900 font-poppins min-w-full min-h-screen p-6">
    <NavBar />
    <Hero />
    <About />
    <Pets />
    <Portfolio />
    <Skills />
  </main>
</template>
