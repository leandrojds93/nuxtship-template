<script setup>
const features = [
  {
    title: "Flexibilidade de acesso",
    description:
      "Com o IPTV, você pode acessar o conteúdo em diversos dispositivos.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Qualidade de imagem e som",
    description:
      "O IPTV oferece uma experiência de visualização de alta qualidade, com suporte para crianças e vídeos em alta definição (UHD).",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Estabilidade de sinal",
    description:
      "O IPTV depende de uma conexão estável com a internet para funcionar corretamente.",
    icon: "bx:bxs-data",
  },
  {
    title: "Variedade de conteúdo",
    description:
      "O IPTV oferece uma ampla variedade de conteúdo, incluindo filmes, programas de TV, esportes e muito mais.",
    icon: "bx:bxs-bot",
  },
  {
    title: "Encontre o que você procura",
    description:
      "O IPTV oferece uma interface de usuário intuitiva que facilita a localização do conteúdo desejado.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "Recursos interativos",
    description:
      "Oferecemos recursos interativos, como pausa, retrocesso e gravação de programas ao vivo.",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Streaming de qualidade para você e sua família
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      Assista o que quisere quando quiser, com qualidade e estabilidade
      o melhor serviço de Streaming do Brasil.
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
