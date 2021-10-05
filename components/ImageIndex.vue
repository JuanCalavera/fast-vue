<template>
  <div class="background-main">
    <div class="md:grid md:grid-cols-2 items-center">
        <div class="hidden md:block"></div>
        <div class="rounded-sm bg-green-700 mt-5 mb-5 lg:mt-36 lg:mb-36 p-5 border-green-900 border-t-8 border-l-8 bg-opacity-70">
            <p class="text-3xl text-center text-white">Nós Ajudamos Você a conseguir seu medicamento de alto custo</p>
            <p class="text-white text-center">Já atendemos mais de 4000 demandas judiciais, no prazo estabelecido, da forma certa e no melhor preço</p>
            <div class="flex justify-center items-center my-2 text-center text-white">
                <NuxtLink to="/" class="p-4 mr-2 rounded-full bg-green-900">Peça sua Cotação Agora</NuxtLink>
                <a href="#" target="_blank" rel="noopener noreferrer" class="p-4 rounded-full bg-green-900">Fale agora via Whatsapp</a>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped>
.background-main {
  background-image: url("../assets/img/image-index.jpg");
  @apply bg-fixed;
}
</style>