<template>
  <div class="relative max-w-full bg-white mb-3">
    <div class="lg:flex justify-between items-center mr-3 ml-3">
      <div class="flex items-center">
        <FastLogo class="mx-auto max-w-lg" />
        <p class="text-center mx-auto max-w-xs text-sm md:text-xl lg:text-base">
          Somos especialistas em atender demanda judicial para medicamentos.
        </p>
        <button class="rounded-md p-2 block md:hidden bg-green-900">
          <MenuIcon/>
        </button>
      </div>
      <div class="hidden sm:flex md:hidden justify-center items-center">
        <a
          href="#"
          target="_blank"
          rel="noopener noreferrer"
          class="
            bg-green-900
            p-3
            rounded-full
            text-white text-center text-sm
            mr-2
          "
          >Ligue Agora 0800 604 8002</a
        >
        <NuxtLink
          to="/"
          class="bg-green-900 p-3 rounded-full text-white text-center text-sm"
          >Peça sua cotação agora</NuxtLink
        >
      </div>
      <div class="hidden lg:flex mr-2 ml-2">
        <input
          type="text"
          name=""
          id=""
          class="border-green-900 p-2 rounded-l-lg border-2"
        />
        <button type="submit" class="rounded-r-lg p-2 bg-green-900 text-white">
          Search
        </button>
      </div>
      <div class="flex lg:hidden md:justify-center">
        <div class="flex">
          <a
            href="#"
            target="_blank"
            rel="noopener noreferrer"
            class="
              bg-green-900
              p-3
              rounded-full
              text-white text-center text-sm
              mr-2
            "
            >Ligue Agora 0800 604 8002</a
          >
          <NuxtLink
            to="/"
            class="bg-green-900 p-3 rounded-full text-white text-center text-sm"
            >Peça sua cotação agora</NuxtLink
          >
        </div>
      </div>
      <div class="flex justify-center lg:hidden m-3">
        <input
          type="text"
          name=""
          id=""
          class="border-green-900 p-2 w-full rounded-l-lg border-2"
        />
        <button type="submit" class="rounded-r-lg p-2 bg-green-900 text-white">
          Search
        </button>
      </div>
      <div class="hidden lg:flex">
        <div class="flex">
          <a
            href="#"
            target="_blank"
            rel="noopener noreferrer"
            class="
              bg-green-900
              p-3
              rounded-full
              text-white text-center text-sm
              mr-2
            "
            >Ligue Agora 0800 604 8002</a
          >
          <NuxtLink
            to="/"
            class="bg-green-900 p-3 rounded-full text-white text-center text-sm"
            >Peça sua cotação agora</NuxtLink
          >
        </div>
      </div>
    </div>
    <div class="relative max-w-full bg-green-900 text-white hidden md:block">
      <div class="flex content-between items-center">
        <NuxtLink to="/" class="m-5 lg:text-xl">Inicio</NuxtLink>
        <NuxtLink to="/" class="m-5 lg:text-xl"
          >Política de Privacidade e Segurança</NuxtLink
        >
        <NuxtLink to="/" class="m-5 lg:text-xl">Cotação</NuxtLink>
        <NuxtLink to="/" class="m-5 lg:text-xl">Loja</NuxtLink>
        <NuxtLink to="/" class="m-5 lg:text-xl">Fast Blog</NuxtLink>
        <NuxtLink to="/" class="m-5 lg:text-xl">Sobre</NuxtLink>
      </div>
    </div>
  </div>
</template>