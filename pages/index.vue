<script setup lang="ts">
import SocBut from "~/components/main_page/SocBut.vue";
import AboutBut from "~/components/main_page/AboutBut.vue";
import ThanksBut from "~/components/main_page/ThanksBut.vue";
</script>

<template>
  <div class="min-h-screen bg-zinc-900 xl:h-full pb-4">
    <div class="pt-12 xl:pt-12 2xl:pt-32 xl:mx-auto xl:mb-4 lg:mb-16 w-full md:w-1/2 animate-in fade-in-5 duration-1000 flex flex-col items-center">
      <img src="../assets/img/komar.jpg" class="rounded-full size-24 xl:size-36">
      <div class="md:flex md:flex-row xl:w-auto mt-4 md:mt-8 flex flex-col items-center">
        <h1 class="text-white text-xl md:text-4xl lg:text-4xl font-semibold tracking-normal">Привет! Меня зовут </h1>
        <div class="bg-gradient-to-r from-indigo-400 to-indigo-600 bg-clip-text text-transparent text-3xl lg:text-4xl font-bold mt-2 md:mt-0 md:ml-2 type-mynames"></div>
      </div>
    </div>
    <div class="grid xl:grid-cols-2 xl:grid-rows-1 grid-cols-1 grid-rows-2 gap-y-4 xl:gap-x-16 w-9/12 xl:w-6/12 mb-12 lg:flex-row mx-auto mt-8 xl:mt-12">
      <AboutBut class="animate-in fade-in-5 duration-1000" />
      <SocBut class="animate-in fade-in-5 duration-1000"/>
    </div>
    <div class="mx-auto w-9/12 xl:w-3/12 -mt-6 xl:mt-0">
      <ThanksBut class="animate-in fade-in-5 duration-1000"/>
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