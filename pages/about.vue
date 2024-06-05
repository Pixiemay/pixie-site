<script setup lang="ts">
import AboutComp from "~/components/about_page/aboutComp.vue";
import CheComp from "~/components/about_page/cheComp.vue";
</script>

<template>
  <div class="w-full bg-zinc-900 lg:h-screen xl:h-full 2xl:h-screen xl:pt-12 2xl:pt-24 pb-16">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-8 xl:ml-28 2xl:ml-64 pt-16 lg:pt-4 lg:mx-64 flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-12 xl:ml-32 2xl:ml-72 lg:mt-0 mt-2 bg-gradient-to-r from-violet-400 to-pink-400 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 w-48">Обо мне</h1>
    <div class="flex xl:flex-row flex-col -ml-4 animate-in fade-in-5 duration-1000">
      <div class="grid grid-cols-1 grid-rows-2 2xl:gap-y-8 w-full xl:w-6/12 h-5/6 ml-12 xl:ml-24 2xl:ml-72 mt-16">
        <about-comp/>
        <che-comp class="-mt-4 xl:mt-0" />
      </div>
      <div class="animate-in fade-in-5 duration-1000 xl:w-5/6 2xl:w-5/6 mt-20 xl:mt-4 items-center">
        <h1 class="text-4xl mb-4 mx-auto -mt-12 font-bold bg-gradient-to-r from-violet-400 to-pink-400 bg-clip-text text-transparent w-4/6">
          Мои проекты
        </h1>
        <div class="mx-auto w-5/6 xl:w-5/6 2xl:w-9/12 xl:pb-16 grid gap-y-4 xl:grid-cols-2 xl:grid-rows-1 grid-cols-1 grid-rows-2">
        </div>
      </div>
    </div>
  </div>
</template>