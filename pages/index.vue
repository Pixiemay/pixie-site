<script setup lang="ts">
import SocBut from "~/components/SocBut.vue";
import AboutBut from "~/components/AboutBut.vue";
</script>

<template>
  <div class="min-h-screen bg-zinc-900 xl:h-full">
    <div class="pt-16 xl:pt-48 xl:mx-auto xl:mb-4 lg:mb-16 w-full md:w-1/2 animate-in fade-in-5 duration-1000 flex flex-col items-center">
      <img src="../assets/img/komar.jpg" class="rounded-full w-28 md:w-36 lg:w-32 xl:w-36">
      <div class="md:flex md:flex-row xl:w-auto xl:mx-52 mt-8 md:mt-8 flex flex-col items-center">
        <h1 class="text-white text-2xl md:text-4xl lg:text-4xl font-semibold tracking-normal">Привет! Меня зовут </h1>
        <span class="bg-gradient-to-r from-indigo-400 to-indigo-600 bg-clip-text text-transparent text-4xl lg:text-4xl font-bold mt-2 md:mt-0 md:ml-2 type-mynames"></span>
      </div>
    </div>
    <div class="lg:grid grid-cols-2 grid-rows-1 lg:gap-4 lg:w-6/12 pb-12 lg:flex-row mx-auto w-56 -mt-8 xl:mt-0">
      <AboutBut class="animate-in fade-in-5 duration-1000 mb-4 lg:mb-0" />
      <SocBut class="animate-in fade-in-5 duration-1000"/>
    </div>
  </div>
</template>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}
</style>
