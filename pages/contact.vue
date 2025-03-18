<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Suporte / Contato</template>
      <template v-slot:desc>Entre em contato conosco preenchendo o formulário abaixo.</template>
    </LandingSectionhead>

    <div class="grid md:grid-cols-2 gap-10 mx-auto max-w-4xl mt-16">
      <div>
        <h2 class="font-medium text-2xl text-gray-800">
          Para atendimento imediato
        </h2>
        <p class="text-lg leading-relaxed text-slate-500 mt-3">
          Entre em contato atavés do whatsapp:
          <a href="https://wa.me/5534984164210" class="text-blue-500">+5534984164210</a> ou ligue para
          (34) 9 8416-4210.
          Atendimento de segunda a sexta das 8h às 18h.
        </p>
        <div class="mt-5">
          <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:map-marker" />
            <span>Monte Carmelo - MG, Brasil</span>
          </div>
          <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:envelope" /><a
              href="mailto:leandro.junio.duarte@gmail.com"
              >leandro.junio.duarte@gmail.com</a
            >
          </div>
          <!-- <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:phone" /><a
              href="tel:+1 (234) 5678 999"
              >+1 (234) 5678 999</a
            >
          </div> -->
        </div>
      </div>
      <div>
        <LandingContactform />
      </div>
    </div>
  </LandingContainer>
</template>
