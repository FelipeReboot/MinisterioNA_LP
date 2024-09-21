<script>
    import Header from "./Header.svelte";
    import SectionWrapper from "./SectionWrapper.svelte";
    import CTAs from "./CTAs.svelte";

</script>

<SectionWrapper>
    <Header /> 
    <div
        class=" flex flex-col gap-10 flex-1 itens-center jusify-center pb-6 md:pb-9"
    >
        <h2
            class="text-4xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1200px]
        mx-auto w-full text-center font-semibold"
        >
            Uma <span class="text-[#32746D]">Comunidade</span>
            de <span class="text-slate-600"> Fé </span>
        </h2>
        <p
            class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full"
        >
            Junte-se a uma comunidade ativa e vibrante de irmãos em <span
                class="text-indigo-400">Cristo,</span
            >
            encontre um lugar de acolhimento e vitória sobre
            <span class="italic">todo</span> o mal.
        </p>
    </div>

    <CTAs /> <!-- Botão de conversao imediata-->

  <!-- Linha com losangos --> 
  <div class="relative flex items-center justify-center pt-24 pb-20">
    <div class="absolute inset-x-0 flex items-center">
        <div class="flex-grow border-t-2 border-gray-800"></div>
        <div class="px-4">
            <i class="fa-solid fa-cross text-gray-800"></i> <!-- Ícone de cruz -->
        </div>
        <div class="flex-grow border-t-2 border-gray-800"></div>
    </div>
</div>

</SectionWrapper>
