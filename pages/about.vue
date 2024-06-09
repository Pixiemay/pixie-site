<script setup lang="ts">
import AboutComp from "~/components/about_page/aboutComp.vue";
import CheComp from "~/components/about_page/cheComp.vue";
</script>

<template>
  <div class="w-full bg-zinc-900 h-full xl:h-screen xl:pt-12 2xl:pt-24 pb-16">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-8 xl:ml-28 2xl:ml-64 pt-12 lg:pt-4 lg:mx-64 flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-12 xl:ml-32 2xl:ml-72 lg:mt-0 mt-2 bg-gradient-to-r from-violet-400 to-pink-400 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 w-48">Обо мне</h1>
    <div class="flex xl:flex-row flex-col animate-in fade-in-5 duration-1000">
      <div class="grid grid-cols-1 grid-rows-2 gap-y-8 xl:gap-y-20 w-full xl:w-6/12 h-2/6 mx-8 xl:ml-24 2xl:ml-72 mt-8">
        <about-comp/>
        <che-comp />
      </div>
    </div>
  </div>
</template>