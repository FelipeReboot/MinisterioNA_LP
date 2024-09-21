<script>
    import SectionWrapper from "./SectionWrapper.svelte";
    export let backgroundImgSrc = "/assets/levandoamor.jpeg";
    export let title = "Levando Amor Onde Há Dor";
    export let description =
        "Um projeto que busca levar o amor de Jesus ao próximo, atuando em locais como orfanatos, asilos, comunidades carentes e nas ruas.";
</script>

<SectionWrapper id="Levando">
    <div
        class="relative h-screen flex items-center justify-center text-center p-8 md:p-14"
    >
        <!-- Foto de fundo com filtro cinza -->
        <div
            class="absolute inset-0 bg-cover bg-center"
            style={`background-image: url(${backgroundImgSrc});background-size: cover`}
        >
            <!-- Filtro cinza sobre a imagem -->
            <div class="absolute inset-0 bg-gray-900 bg-opacity-50"></div>
        </div>

        <!-- Conteúdo sobre a foto de fundo -->
        <div class="relative z-10 text-white p-6 md:p-12">
            <h1 class="text-5xl md:text-6xl font-bold mb-4">{title}</h1>
            <p class="text-lg md:text-xl">{description}</p>
        </div>
    </div>

    <!-- Linha de separação -->
    <div class="w-full border-t-2 border-gray-300 my-10"></div>

    <!-- Bloco "Conheça o nosso trabalho" -->
    <div
        class="flex flex-col items-center justify-center gap-8 py-5 px-3 bg-[#FFFEF9]"
    >
        <h2
            class="text-3xl sm:text-4xl md:text-5xl font-bold text-center text-[]"
        >
            Conheça o nosso <span class="text-[#32746D]">Trabalho </span>
        </h2>
        <p class="text-lg sm:text-xl md:text-2xl text-center text-gray-700">
            Somos uma organização sem fins lucrativos, atuamos no município de
            Campo Largo – PR desde março de 2017, com o objetivo de <span class="font-bold text-[#32746D]">
            colocar em prática nossa responsabilidade social</span>. 
            Realizamos ações voltadas para o público em situação de <span class="font-bold text-[#32746D]">
            vulnerabilidade social</span>, sejam eles
            idosos residentes em lares, famílias de comunidades carentes,
            moradores em situação de rua, tal como crianças e adolescentes
            residentes em instituições lares. Nos ajude a <span
                class="text-[#32746D]
            font-bold">transformar vidas</span
            >.
        </p>
    </div>

    <!-- Botões de CTA -->
    <div
        class="flex flex-col md:flex-row items-center justify-center gap-4 py-10"
    >
        <!-- Botão para o Facebook -->
        <a
            href="https://www.facebook.com/levandoamorondehador/"
            target="_blank"
            class="specialBtn"
        >
            <p class="text-base sm:text-lg md:text-xl hover:text-indigo-400 duration-200">
                <i class="fa-brands fa-square-facebook"></i> Facebook
            </p>
        </a>

        <!-- Botão para o instagram -->
        <a
            href="https://www.instagram.com/levandoamorondehador/"
            target="_blank"
            class="specialBtn"
        >
            <p class="text-base sm:text-lg md:text-xl hover:text-indigo-400 duration-200">
                <i class="fa-brands fa-instagram"></i> Instagram
            </p>
        </a>

        <!-- Botão para o site oficial -->
        <a
            href="https://levandoamorong.wixsite.com/laohd"
            target="_blank"
            class="specialBtn"
        >
            <p class="text-base sm:text-lg md:text-xl hover:text-indigo-400 duration-200">
                <i class="fa-solid fa-heart"></i> Levando Amor
            </p>
        </a>

        <!-- Botão para doações -->
        <a
            href="https://doemna.vercel.app/"
            target="_blank"
            class="specialBtn"
            >
            <p class="text-base sm:text-lg md:text-xl hover:text-indigo-400 duration-200">
                <i class="fa-solid fa-hand-holding-dollar "></i> Contribua
            </p>
        </a>
    </div>

    <!-- Linha com losangos -->
    <div class="relative flex items-center justify-center pt-24 pb-20">
        <div class="absolute inset-x-0 flex items-center">
            <div class="flex-grow border-t-2 border-gray-800"></div>
            <div class="px-4">
                <i class="fa-solid fa-wine-glass text-gray-800"></i>
                <!-- Ícone de calice -->
            </div>
            <div class="flex-grow border-t-2 border-gray-800"></div>
        </div>
    </div>
</SectionWrapper>

>
