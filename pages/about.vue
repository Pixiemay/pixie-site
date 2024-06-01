<script setup lang="ts">

</script>

<template>
  <div class="w-full bg-zinc-900 lg:h-screen xl:h-full xl:pt-16">
    <NuxtLink to="/" class="animate-in fade-in-5 duration-1000">
      <div class="ml-[40px] pt-16 lg:pt-16 lg:mx-[260px] flex flex-row text-white hover:text-gray-300 animate-in fade-in-5 duration-1000">
        <icon name="material-symbols:arrow-left-alt" class="size-8 md:size-12 mr-2 "/>
        <h2 class="font-semibold text-lg md:text-xl w-40 md:w-48 md:pt-2">Вернуться назад</h2>
      </div>
    </NuxtLink>
    <h1 class="ml-[40px] lg:ml-72 lg:mt-0 mt-2 bg-gradient-to-r from-violet-400 to-pink-400 bg-clip-text text-transparent text-4xl font-bold animate-in fade-in-5 duration-1000 w-48">Обо мне</h1>
    <div class="grid grid-cols-1 lg:grid-cols-2 grid-rows-1 gap-2 lg:gap-y-24 lg:gap-x-16 xl:gap-y-8 mx-auto w-8/12 h-2/6 animate-in fade-in-5 duration-1000">
      <div class="mt-16 mx-auto h-72 lg:h-56 xl:h-64 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 xl:py-10 hover:scale-105 duration-500 ease-in-out">
        <Icon name="gravity-ui:person" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Обо мне</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Меня зовут Андрей, мне 16 лет. Я на 1 курсе колледжа и учусь по специальности программиста.
          Изучаю веб разработку и создание сайтов.</h2>
      </div>
      <div class="mt-8 xl:mt-16 mx-auto h-84 lg:h-56 xl:h-5/6 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 xl:py-6 hover:scale-105 duration-500 ease-in-out">
        <Icon name="gravity-ui:folder-open" class="text-white size-12"/>
        <h1 class="text-white text-2xl font-bold mt-2">Чем я занимаюсь</h1>
        <h2 class="text-gray-400 font-semibold text-base md:text-lg mt-2">Я являюсь администратором сервера Lonya SMP, параллельно этому занимаюсь стримингом на твиче и изучением сферы веб разработки.
        Так же имею опыт в работе с Тех. Администрировании серверов майнкрафт.</h2>
      </div>
    </div>
    <div class="mt-8 animate-in fade-in-5 duration-1000">
      <h1 class="text-4xl font-bold mx-auto bg-gradient-to-r from-violet-400 to-pink-400 bg-clip-text text-transparent w-64">
        Мои проекты
      </h1>
      <div class="grid grid-cols-1 lg:grid-cols-2 grid-rows-1 gap-2 lg:gap-y-24 lg:gap-x-8 xl:gap-y-8 mx-auto w-5/6 xl:w-2/6 pb-16">
        <div class="mt-8 xl:mt-16 h-76 xl:h-5/6 lg:h-56 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 hover:scale-105 duration-500 ease-in-out w-64 xl:w-72 mx-auto">
          <img src="../assets/img/minestar.jpg" class="size-48 xl:size-52 rounded-3xl mx-auto">
          <h1 class="bg-gradient-to-r from-indigo-500 to-blue-500 bg-clip-text text-transparent text-3xl font-bold w-32 mx-auto mt-4">MineStar</h1>
          <h2 class="text-gray-400 font-semibold text-base text-center md:text-lg mt-2">Мой первый сервер майнкрафт, на котором я получил больше всего опыта.  Май 2021г. - Март 2024г.</h2>
        </div>
        <div class="mt-8 xl:mt-16 h-76 xl:h-5/6 lg:h-56 bg-zinc-800 hover:bg-zinc-700/60 rounded-3xl px-8 py-8 hover:scale-105 duration-500 ease-in-out w-64 xl:w-72 mx-auto" href="https://discord.gg/JxqujFfRNE">
          <img src="../assets/img/aura.png" class="size-48 xl:size-52 rounded-3xl mx-auto">
          <h1 class="bg-gradient-to-r from-fuchsia-600 to-purple-600 bg-clip-text text-transparent text-3xl font-bold w-20 mx-auto mt-4">Aura</h1>
          <h2 class="text-gray-400 font-semibold text-base text-center md:text-lg mt-2">Сервер на котором я являлся администратором совместно с An1by. Март 2024г. - Июнь 2024г.</h2>
        </div>
      </div>
    </div>
  </div>
</template>