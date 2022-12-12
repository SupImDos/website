<script setup>
import { useDark, useToggle } from '@vueuse/core';
import IconDarkMode from '../icons/IconDarkMode.vue'

const isDark = useDark();
const toggleDark = useToggle(isDark);
</script>

<template>
  <nav class="flex flex-row-reverse pb-12">
    <a class="w-6 cursor-pointer" @click="toggleDark()">
      <IconDarkMode class="fill-black dark:fill-white" />
    </a>
  </nav>
</template>
