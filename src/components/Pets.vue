<script setup>
import Frank from '../assets/images/frank.jpg'
import Marley from '../assets/images/marley.jpg'
</script>

<template>
  <section class="flex flex-col place-items-center place-content-center pb-6">
    <h3 class="text-lg md:text-3xl py-2 text-black dark:text-white font-normal">Pets</h3>
    <div class="flex flex-row gap-8 text-sm md:text-base italic text-center text-gray-800 dark:text-gray-200">
      <figure>
        <img class="rounded-xl w-64" :src="Frank">
        <figcaption>Frank</figcaption>
        <figcaption>(Mini Dachshund)</figcaption>
      </figure>
      <figure>
        <img class="rounded-xl w-64" :src="Marley">
        <figcaption>Marley</figcaption>
        <figcaption>(Golden Retriever)</figcaption>
      </figure>
    </div>
    <div class="text-base md:text-xl text-justify leading-6 text-gray-800 dark:text-gray-200 max-w-xl pt-5">
      <p>
        These are my dogs; Frank and Marley. I use them as logos, mascots and
        avatars online.
      </p>
    </div>
  </section>
</template>