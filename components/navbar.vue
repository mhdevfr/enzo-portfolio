<template>
  <div class="absolute top-0 w-3/4 h-20 flex items-center rounded-md bg-clip-padding backdrop-filter backdrop-blur-md bg-opacity-50 border border-gray-100 justify-center">
    <div class="w-1/6 m-8 brico-800">
      <nuxt-link to="/">
        <h1 class="text-3xl flex items-center">
          EEDev
        </h1>
      </nuxt-link>
    </div>
    <div class="w-5/6 justify-center items-center m-8 brico-200">
      <ul class="flex justify-end">
        <li>
          <nuxt-link
            to="/"
            class="px-10 py-2 underline-offset-4 underline decoration-sky-500"
            >Home</nuxt-link
          >
          <nuxt-link to="#about" class="px-10 py-2">About me</nuxt-link>
          <nuxt-link to="/contact" class="px-4 mx-4 py-2 bg-gray-100 text-black rounded-md">Contact</nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped lang="css"></style>
