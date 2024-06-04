<script setup lang="ts">
import DonComp from "~/components/thanks_page/donComp.vue";
import TwitchComp from "~/components/thanks_page/twitchComp.vue";
import BoostyComp from "~/components/thanks_page/boostyComp.vue";
</script>

<template>
  <div class="w-full bg-zinc-900 h-full xl:h-screen xl:pt-12 2xl:pt-24 pb-12  ">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-8 xl:ml-28 2xl:ml-64 pt-16 lg:pt-4 lg:mx-64 flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-12 xl:ml-32 2xl:ml-64 lg:mt-0 mt-2 bg-gradient-to-r from-emerald-400 to-emerald-700 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 w-68">Благодарность</h1>
    <div class="xl:grid xl:grid-cols-3 xl:grid-rows-1 flex flex-col gap-y-12 w-4/6 mx-auto mt-12 xl:mt-24 animate-in fade-in-5 duration-1000">
      <don-comp class="animate-in fade-in-5 duration-1000" />
      <twitch-comp class="animate-in fade-in-5 duration-1000" />
      <boosty-comp class="animate-in fade-in-5 duration-1000" />
    </div>
  </div>
</template>