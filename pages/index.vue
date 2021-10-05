<template>
  <div>
    <MainHeader />
    <ImageIndex />
    <div class="main-container">
      <h1 class="text-center text-4xl m-5 text-green-900">
        Nós da Fast Medicamentos somos especialistas em facilitar a cotação da
        sua demanda de medicamentos.
      </h1>
      <p class="text-center text-green-900 m-5">
        A Fast é a única empresa especializada no ramo de entrega de
        medicamentos de demandas judiciais e privadas. E sim acontece por que
        somos realmente diferentes.
      </p>
      <div class="grid grid-cols-2">
        <div>
          <h2>
            VOCÊ PRECISA DE AJUDA? TENHA SUAS 3 COTAÇÕES COM NOSSO PARCEIRO
          </h2>
          <hr>
          <p class="text-green-900">
            Se você tem dúvida como conseguir seu medicamento de alto custo com
            segurança nós lhe daremos suporte! Caso você precise de uma cotação
            além da nossa, o nosso parceiro Preço Medicamento pode fazer sua
            cotação clique abaixo e saiba mais.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $axios }) {
    const posts = await $axios.$get("/post-blog");
    return { posts };
  },
};
</script>

<style scoped>
@layer components {
  .main-container {
    @apply max-w-screen-lg mx-auto;
  }
  .main-container ul {
    @apply lg:my-5 my-3;
  }
  .main-container li {
    @apply mb-2;
  }
  .main-container h1 {
    @apply text-4xl;
  }
  .main-container h2 {
    @apply text-lg text-green-900 font-bold;
  }
}
</style>
