<template>
  <footer>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-10 md:gap-28">
      <div>
        <div class="flex gap-2 mb-5">
          <h1 class="text-black font-bold text-2xl">Тирасполь<span class="text-secondary">IT</span>ПМР</h1>
         <img width="50px" height="50px" src="https://media4.giphy.com/media/dZKgLiWvXptobPH0WT/giphy.gif?cid=ecf05e47rpq9n26egvq6aqtem97mobbolfr3rfod19p4f2y1&rid=giphy.gif&ct=s" alt="">
        </div>
        <p class="text-white leading-loose tracking-wide w-full md:w-[80%]">Топ языки програмирования в Тирасполе</p>
        <div class="flex justify-end md:justify-start -mt-7 md:mt-3">
          <img class="w-12 md:-translate-x-10 scale-x-[-1] md:scale-100" src="https://media0.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif?cid=ecf05e47n8hbnqmpbnjcv2dxngbxfqclttnmtom4h32bobzi&rid=giphy.gif&ct=s" alt="">
        </div>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 justify-center gap-12 text-white">
        <div>
          <h3 class="mb-4 font-bold text-2xl md:text-lg">О нас</h3>
          <div class="flex flex-col gap-3">
            <a href="https://www.tadviser.ru/index.php/%D0%A1%D1%82%D0%B0%D1%82%D1%8C%D1%8F:%D0%A0%D0%B5%D0%B9%D1%82%D0%B8%D0%BD%D0%B3_%D0%B2%D0%BE%D1%81%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8_%D1%8F%D0%B7%D1%8B%D0%BA%D0%BE%D0%B2_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F#:~:text=%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%B5%20%D0%BC%D0%B5%D1%81%D1%82%D0%BE%20%D1%81%D0%BE%D1%85%D1%80%D0%B0%D0%BD%D0%B8%D0%BB%20JavaScript.,%D0%9F%D1%8F%D1%82%D0%BE%D0%B5%20%D0%BF%D1%8F%D1%82%D1%83%D1%8E%20%D1%81%D1%82%D1%80%D0%BE%D1%87%D0%BA%D1%83%20%D0%B7%D0%B0%D0%BD%D1%8F%D0%BB%20%D0%A1%23." class="hover:underline">Топ ЯП</a>
            <a href="https://github.com/424Nkita-Csharsfta4" class="hover:underline">Админ</a>
          </div>
        </div>
        <div>
          <h3 class="mb-4 font-bold text-2xl md:text-lg">Технологии</h3>
          <div class="flex flex-col gap-3">
            <a href="https://vuejs.org/" class="hover:underline">Vue js</a>
            <a href="https://vuetifyjs.com/en/" class="hover:underline">Vuetify</a>
            <a href="https://tailwindcss.com/" class="hover:underline">Tailwind</a>
          </div>
        </div>
      </div>
    </div>

    <div class="grid place-items-center my-20 w-full ">
      <div class="flex items-center gap-10">
        <a href="https://github.com/424Nkita-Csharsfta4" class="bg-secondary h-12 w-12 grid place-items-center rounded-md">
          <img src="data:image/png;base64,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" alt="">
        </a>
        <a href="https://www.youtube.com/channel/UCoY4wt5Td9cTV7RjPLIqXpw" class="bg-secondary h-12 w-12 grid place-items-center rounded-md">
          <img src="data:image/jpeg;base64,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" alt="">
        </a>
        <a href="https://vk.com/php1234python" class="bg-secondary h-12 w-12 grid place-items-center rounded-md">
          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHcAAABDCAMAAACRDGoDAAAAk1BMVEX///8AAABDiO0xf+vHx8fExMTf39/l5eXq6ur///3W1tb8//6jo6M6hOzR4fTi4uIrKyytra3W5fXg6fdTjuj19fWXu+8xMTGXl5chISHOzs5lZWVNTU05OTp0dHR+fn4ZGRns8vlxouy5zvBLjOuhv+9eluvG2vUceOpWVlZAQECAq+sTExULCwy4uLhrneyQs+5o+6ETAAABz0lEQVRYhe2VW5OiMBBGv4agJJAV1KiAIDqurhec/f+/bjsszs7j+MLOQ58CqtJJ1Uk3uQCCIAiCIAiCIAivoLGf//DMFwm0Hs2bHGw4YN8wnncVBh+Ei7GsGsvgk/dtPG9gj0d+jkGwDMKfPuYiFRlgVgIlvxPFDagZYEwcKaWiGFMfiyPujJ6huB/2ZW/CSerTQZ9/nfUpXPn/O6FsTQ02GXIyqKig2oE2wKUpyRPldOUBipyhPOpDKqWMsvgVrz3gHOrzib92hd4LpIR0W5Ji9QQuq1CkQNVwkjTlMkx4UFzSxM+GQzFmxMlftq94g3Cub3qxT2xgn/lmlLOavKviyKbD+t4W1Hu54KruWjKGyHdiylPJqejuHb3ktUsN7RJ9s8981cTnW1dFjObKkV2BrImi6+CNKY8NmZJ2VA7eB5kp85KXK53gHDj9Hg7ecpqSS6+oM27seBI52o86917XeK/b+ap7r6OLUcXm614cvTi4vdvT75Pt1/Osbbv6gfQCV1coL/frA6jZ2+yGOudZ8dga0zlUvOS8F3HTrr+uZf7uX2u9fbz9C/2/zqt/57MNxkvXs1/Mn/fRuAyX0IiX4GetIAiCIAiCIAjfgD8p2h1twqRh7gAAAABJRU5ErkJggg==" alt="">
        </a>
      </div>
      <p class="md:text-lg font-medium text-center text-white mt-8 tracking-wider">
        Frontender is Tirasa
      </p>
    </div>
  </footer>
</template>