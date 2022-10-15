<script setup>
  import category1 from "../assets/images/category/kotlin-original-wordmark.svg"
  import category2 from "../assets/images/category/php-original.svg"
  import category3 from "../assets/images/category/typescript-original.svg"

  const categories = [
    {
      title: 'Kotlink',
      image: category1,
      desc: 'статически типизированный, объектно-ориентированный язык программирования, работающий поверх Java Virtual Machine и разрабатываемый компанией JetBrains. '
    },
    {
      title: 'PHP',
      image: category2,
      desc: 'На сегодняшний день PHP является одним из наиболее распространенных языков веб-программирования. Подавляющие большинство сайтов и веб-сервисов в интернете написано с помощью PHP.'
    },
    {
      title: 'TypeScript',
      image: category3,
      desc: 'TypeScript представляет язык программирования на основе JavaScript.Развитие TypeScript началось в конце 2012 года. '
    },
  ]
</script>

<template>
  <section id="category" class="flex flex-col items-center py-32">
    <h2 class="my-10 text-5xl md:text-6xl font-bold text-black">Набирающие популярность ЯП</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 place-items-center">
      <div v-for="category of categories" :key="category.title" class="text-white grid place-items-center gap-5 text-center">
        <div class="p-10">
          <img :src="category.image" class="w-full" alt="category1">
        </div>
        <h3 class="text-3xl font-bold">{{ category.title }}</h3>
        <p class="w-3/4">{{ category.desc}}</p>
      </div>
    </div>
  </section>
  <section class="grid grid-flow-col grid-cols-1 md:grid-cols-2 md:gap-10 items-center">
    <div class="md:p-10">
      <img src="../assets/images/yap.png" alt="category2-img">
    </div>
    <div class="text-center flex flex-col items-center">
      <h2 class="text-5xl md:text-6xl font-bold text-orange">Список популярных ЯП</h2>
      <div class="flex items-center gap-5">
        <h2 class="text-5xl md:text-6xl font-bold text-white">2021-2022</h2>
        <img src="https://media4.giphy.com/media/xSVQgqlSTMXYs/giphy.gif?cid=ecf05e47n6murdvga5e3em17rlxjvv3qdzr6y13gbjwgf8t7&rid=giphy.gif&ct=s" class="w-9 md:w-12" alt="head2">
      </div>
      <p class="mt-8 md:mt-12 text-white text-lg md:text-xl w-full md:w-[80%]">Наибольшей популярностью на сегодняшнем рынке труда пользуются программисты 1С, программисты PHP, Cи, C++, C#, Java, разработчики баз данных, тестировщики ПО.</p>
    </div>
  </section>
</template>