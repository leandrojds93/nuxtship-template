<script setup>
definePageMeta({
  layout: "landing",
});

const pricing = [
  {
    name: "Mensal",
    price: "R$25,00",
    popular: false,
    features: [
      "Mensal",
      "Conexão Simultânea: 01",
      "Canais: SD HD FHD 4K",
      "Filmes e Séries On Demand",
      "Suporte sob demanda",
      "Sistema anti-travas",
    ],
    button: {
      text: "ASSINAR",
      link: "/",
    },
  },
  {
    name: "Trimestral",
    price: "R$59,99",
    popular: true,
    features: [
      "Três mêses",
      "Conexão Simultânea: 03",
      "Canais: SD HD FHD 4K",
      "Filmes e Séries On Demand",
      "Suporte diario",
      "Sistema anti-travas",
    ],
    button: {
      text: "ASSINAR",
      link: "#",
    },
  },
  {
    name: "Anual",
    price: "R$199,99",
    popular: true,
    features: [
      "Doze mêses",
      "Conexão Simultânea: 03",
      "Canais: SD HD FHD 4K",
      "Filmes e Séries On Demand",
      "Suporte diario + 3 Servidores",
      "Sistema anti-travas",
    ],
    button: {
      text: "ASSINAR",
      link: "#",
    },
  },
];
</script>

<template>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Valores</template>
      <template v-slot:desc
        >Valores fixos de acordo com o plano contratado.</template
      >
    </LandingSectionhead>

    <div class="grid md:grid-cols-3 gap-10 mx-auto max-w-screen-lg mt-12">
      <LandingPricing v-for="item of pricing" :plan="item" />
    </div>
  </LandingContainer>
</template>
