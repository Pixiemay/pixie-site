<script setup lang="ts">

import BoostyBut from "~/components/soc_page/BoostyBut.vue";
import TwitchBut from "~/components/soc_page/TwitchBut.vue";
import DiscordBut from "~/components/soc_page/DiscordBut.vue";
import GithubBut from "~/components/soc_page/GithubBut.vue";
import TelegramBut from "~/components/soc_page/TelegramBut.vue";
</script>

<template>
  <div class="w-screen h-full bg-zinc-900 lg:h-screen xl:h-full 2xl:h-screen xl:pt-4">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-8 pt-16 lg:pt-16 lg:mx-64 flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-[40px] lg:ml-64 lg:mt-0 mt-2 bg-gradient-to-r from-blue-300 to-cyan-300 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 ">Социальные сети</h1>
    <div class="grid grid-cols-1 lg:grid-cols-2 grid-rows-1 lg:grid-rows-2 gap-y-6 lg:gap-y-8 lg:gap-x-16 mx-auto w-7/12 mt-16 animate-in fade-in-5 duration-1000 pb-16">
      <TelegramBut />
      <BoostyBut />
      <TwitchBut />
      <DiscordBut />
      <GithubBut />
    </div>
  </div>
</template>

<style scoped>

</style>