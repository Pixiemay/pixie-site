<script setup lang="ts">

</script>

<template>
  <div class="w-screen h-full bg-zinc-900 lg:h-screen xl:pt-16">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-[40px] pt-16 lg:pt-16 lg:mx-[260px] flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-[40px] lg:ml-64 lg:mt-0 mt-2 bg-gradient-to-r from-blue-300 to-cyan-300 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 ">Социальные сети</h1>
    <div class="grid grid-cols-1 lg:grid-cols-2 grid-rows-1 lg:grid-rows-2 lg:gap-y-24 lg:gap-x-16 mx-auto w-8/12 xl:h-3/6 h-4/6 animate-in fade-in-5 duration-1000">
      <a class="mt-16 mx-auto h-56 lg:h-56 xl:h-48 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 hover:cursor-pointer hover:scale-105 duration-500 ease-in-out" href="https://t.me/pixiemaysttv">
        <Icon name="gravity-ui:logo-telegram" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Telegram</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Мой телеграмм канал через который можно со мной связаться</h2>
      </a>
      <a href="https://boosty.to/pixiemay" class="mt-8 lg:mt-16 mx-auto h-60 lg:h-56 xl:h-48 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 hover:cursor-pointer hover:scale-105 duration-500 ease-in-out">
        <Icon name="simple-icons:boosty" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Boosty</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Мой бусти в котором вы можете меня поддержать средствами</h2>
      </a>
      <a href="https://www.twitch.tv/pixiemays" class="mt-8 h-52 lg:h-56 md:h-56 xl:h-48 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-6 hover:cursor-pointer hover:scale-105 duration-500 ease-in-out">
        <Icon name="simple-icons:twitch" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Twitch</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Мой твич канал на котором ведутся мои стримы</h2>
      </a>
      <a href="https://discord.gg/8M2HgmNcuz" class="mt-8 mb-8 h-52 xl:h-48 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-6 hover:cursor-pointer hover:scale-105 duration-500 ease-in-out">
        <Icon name="ic:baseline-discord" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Discord</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Мой дискорд сервер где вы сможете найти меня</h2>
      </a>
    </div>
  </div>
</template>

<style scoped>

</style>