<script setup lang="ts">
import SocBut from "~/components/SocBut.vue";
import AboutBut from "~/components/AboutBut.vue";
</script>

<template>
  <div class="w-screen h-screen bg-zinc-900 fixed">
    <div class="mt-24 xl:mt-48 lg:mb-16 mx-24 md:mx-44 lg:mx-auto w-1/2 h-1/6 xl:h-2/6 animate-in fade-in-5 duration-1000">
      <img src="../assets/img/komar.jpg" class="rounded-full size-28 md:size-36 lg:size-32 xl:size-36 mx-auto md:mx-44 lg:mx-auto">
      <div class="w-screen md:flex md:flex-row xl:mx-52">
        <h1 class="text-white text-2xl md:text-4xl lg:text-4xl font-semibold tracking-normal mt-8">Привет! Меня зовут </h1>
        <span class="bg-gradient-to-r from-indigo-400 to-indigo-600 bg-clip-text text-transparent text-4xl lg:text-4xl font-bold mt-2 md:mt-8 ml-8 md:ml-2 type-mynames"></span>
      </div>
    </div>
    <div class="lg:grid grid-cols-2 grid-rows-1 lg:gap-4 w-6/12 xl:-mt-48 mx-auto">
      <AboutBut class="animate-in fade-in-5 duration-1000" />
      <SocBut class="animate-in fade-in-5 duration-1000"/>
    </div>
  </div>
</template>

<style scoped>

</style>