<script>
  import SectionWrapper from "./SectionWrapper.svelte";
</script>

<SectionWrapper id="Missao">
  <div
    class=" flex flex-col gap-5 sm:gap-6 md:gap-10 flex-1
    itens-center justify-center pb-10 mb:pb-14"
  >
    <p class="opacity-50 text-base sm:text-lg md:text-xl text-center">
      Ministerio <span class="text-[#32746D]">Nova Aliança</span>
    </p>
    <h3
      class="text-4xl sm:text=5xl md:text6xl max-w-[1000px] mx-auto
        w-full font-semibold text-center"
    >
      Nossa
      <span class="text-[#32746D]">MISSÃO</span>
    </h3>

    <div
      class="relative flex flex-col md:flex-row items-center
         md:items-start text-center md:text-left"
    >
      <!-- Contêiner da imagem com gradiente -->
      <div class="relative w-full lg:w-1/2 mb-4 lg:mb-0">
        <img
          src="/assets/missao.jpg"
          alt="pessoas orando juntas"
          class="object-cover w-full h-auto rounded-lg z-10"
        />
        <!-- Sombra gradiente sobre a imagem -->
        <div
          class="absolute inset-0 bg-gradient-to-b from-black/60 to-transparent rounded-lg z-0"
        ></div>
      </div>

      <!-- Texto ao lado da imagem -->
      <div
        class="flex flex-col gap-4 sm:gap-7 md:gap-12 lg:gap-15 flex-1 items-center justify-center pb-4 lg:pb-10"
      >
        <p class="p-2 py-0 lg:p-6">No Ministério <span class="font-bold text-[#32746D]">
          Nova Aliança</span>, nossa missão é clara e profundamente enraizada em nossa fé: <span class="font-bold text-[#32746D]">
          fazer a pessoa de Cristo conhecida.</span> Nós acreditamos que Jesus Cristo é o centro de todas as coisas, e é nossa 
          prioridade compartilhar Sua vida, missão e mensagem com o mundo. Queremos 
          que cada pessoa ao se encontrar conosco, tenha a oportunidade de 
          experimentar a <span class="font-bold text-[#32746D]">transformação</span> 
          que só Cristo pode oferecer. Amamos louvar a Deus e glorificá-Lo em todos 
          os aspectos de nossas vidas. Cada momento de adoração é uma expressão do nosso amor e gratidão por tudo que Ele tem 
          feito. Nos reunimos para cantar, orar e celebrar as maravilhas de Seu nome, 
          pois acreditamos que a adoração é um reflexo da nossa devoção e alegria.
          Mas nossa missão não termina apenas na adoração. Nós nos esforçamos para 
          agir ativamente de acordo com os valores de Cristo na comunidade local. 
          Estamos comprometidos em <span class="font-bold text-[#32746D]">
          servir, apoiar e amar</span> nossos vizinhos, refletindo o caráter de Jesus em 
          nossas ações diárias. Acreditamos que o <span class="font-bold text-[#32746D]">
          verdadeiro cristianismo</span> é vivido em prática, não apenas em palavras, 
          promovendo um impacto positivo e duradouro na vida das pessoas ao nosso 
          redor. Convidamos você a se juntar a nós.</p>
      </div>
    </div>
  </div>

  <!-- Linha com losangos -->
  <div class="relative flex items-center justify-center pt-24 pb-20">
    <div class="absolute inset-x-0 flex items-center">
      <div class="flex-grow border-t-2 border-gray-800"></div>
      <div class="px-4">
        <i class="fa-solid fa-rainbow text-gray-800"></i>
        <!-- Ícone de arco iris -->
      </div>
      <div class="flex-grow border-t-2 border-gray-800"></div>
    </div>
  </div>
</SectionWrapper>
