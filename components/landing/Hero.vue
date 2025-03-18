<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/hero.jpg"
        alt="Starship starts the engine"
        loading="eager"
        format="avif"
        width="512"
        height="512"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        O melhor serviço de IPTV do Brasil.
      </h1>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        Assista o que quiser, onde quiser e quando quiser
        com a maior variedade de conteúdos do Brasil e uma enorme gama de
        opções de entretenimento.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="/pricing"
          target="_blank"
          rel="noopener"
          >Planos e Valores</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="https://wa.me/5534984164210?text=Solicitar%20teste%20gr%C3%A1tis!"
          target="_blank"
          >Solicitar teste grátis!</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="https://leandrotv.my.canva.site"
          target="_blank"
          >Loja de aplicativos</LandingLink
        >
      </div>
    </div>
  </main>
</template>
