<script setup>
import Hayden from '../assets/images/hayden.png'
import IconEmail from '../icons/IconEmail.vue'
import IconGithub from '../icons/IconGithub.vue'
import IconLinkedIn from '../icons/IconLinkedIn.vue'
import IconResume from '../icons/IconResume.vue'
</script>

<template>
  <section class="flex flex-col place-items-center place-content-center text-center pb-16">
    <h1 class="text-4xl md:text-6xl py-2 text-emerald-600 dark:text-emerald-400 font-medium">Hayden Richards</h1>
    <h2 class="text-lg md:text-3xl py-2 text-black dark:text-white font-normal">Software Engineer & Data Analyst</h2>
    <p class="text-base md:text-xl py-5 leading-6 text-gray-800 dark:text-gray-200 max-w-xl">
      Software Engineer & Data Analyst from Perth, Western Australia with a
      passion for open-source development and a dedication to creating
      innovative solutions for real-world challenges.
    </p>
    <div class="flex justify-center gap-8 py-3 fill-gray-600 dark:fill-gray-400">
      <a href="https://www.linkedin.com/in/hayden-peter-richards/" class="w-9 md:w-12">
        <IconLinkedIn class="hover:scale-110 duration-200 ease-in-out cursor-pointer" />
      </a>
      <a href="https://github.com/SupImDos/" class="w-9 md:w-12">
        <IconGithub class="hover:scale-110 duration-200 ease-in-out cursor-pointer" />
      </a>
      <a href="mailto:supimdos@gmail.com" class="w-9 md:w-12">
        <IconEmail class="hover:scale-110 duration-200 ease-in-out cursor-pointer" />
      </a>
      <a href="#" class="w-9 md:w-12">
        <IconResume class="hover:scale-110 duration-200 ease-in-out cursor-pointer" />
      </a>
    </div>
    <img class="rounded-full w-72 md:w-96 my-6 bg-gradient-to-b from-emerald-500" :src="Hayden">
  </section>
</template>