<script>
    import SectionWrapper from "./SectionWrapper.svelte";
</script>

<SectionWrapper id="Contato">
    <!-- Sessão de conversão da LP-->
    <section
        class="py-14 md:py-20 flex flex-col gap-8 bg-[#32746D] p-10 text-[#FFFEF9]
        text-center itens-center justify-center"
    >
        <h4 class="text-xl sm:text-2xl md:text-3xl poppins">
            <!-- Titulo chamativo -->
            Para todas as suas perguntas há apenas uma resposta:
            <br /><span class="poppins font-bold">Jesus</span>
        </h4>
        <p class="poppins text-base sm:text-lg md:text-xl">
            &#10013 Se você está em busca de respostas em um mundo que só te
            oferece sofrimento, por redenção por uma vida de erros, por vitória
            em uma história de sucessivas derrotas, o seu lugar é Conosco!
        </p>
    </section>

    <!-- Conteúdo principal: Quem é Jesus -->
    <div
        class="flex flex-col gap-5 sm:gap-6 md:gap-10 flex-1 items-center
        justify-center pb-10 mb:pb-14 p-10 pb-2"
    >
        <h3
            class="text-4xl sm:text-5xl md:text-6xl max-w-[1000px]
            mx-auto w-full font-semibold text-center"
        >
            Quem é
            <span class="text-[#32746D]">Jesus?</span>
        </h3>

        <div
            class="relative flex flex-col md:flex-row items-center
            md:items-start text-center md:text-left max-w-[1200px] mx-auto"
        >
            <!-- Contêiner da imagem -->
            <div class="relative w-full md:w-1/2 mb-4 md:mb-0 pr-0 md:pr-8">
                <img
                    src="/assets/jesus.jpg"
                    alt="ilustração de Jesus"
                    class="object-cover w-full h-auto rounded-lg"
                />
            </div>

            <!-- Texto ao lado da imagem -->
            <div
                class="flex flex-col gap-8 sm:gap-10 md:gap-14
                lg:gap-16 flex-1 items-center md:items-start justify-center
                pb-8 lg:pb-7 text-left"
            >
                <h3 class="text-2xl sm:text-3xl md:text-4xl font-semibold">
                    O maior homem da história
                </h3>

                <p class="poppins text-base sm:text-lg md:text-xl py-2 px-0 md:px-4 leading-relaxed text-justify">
                    <span class="font-bold">Jesus</span> é de fato o personagem
                    histórico mais influente que já existiu. Ele
                    <span class="font-bold text-[#32746D]">ensinou o bem</span>
                    e viveu o que ensinou, e no final,
                    <span class="font-semibold">perdoou</span> até mesmo as
                    pessoas que o condenaram injustamente. Amado por muitos e
                    odiado por tantos outros,
                    <span class="font-bold">esse homem dividiu a história ao meio.</span>
                    No entanto, isso é apenas uma fração do que ele fez. Na verdade,
                    ao cumprir a sua missão, ele
                    <span class="text-[#32746D] font-semibold">levou sobre si nossas dores, maldições, pecados</span>
                    , nossa maldade e cumpriu a justiça de Deus, nos livrando
                    também da própria morte.
                </p>

                <p class="poppins text-base sm:text-lg md:text-xl py-1 px-0 md:px-4 leading-relaxed text-justify">
                    Não somente isso, depois de <span class="font-bold text-[#32746D]">3 dias</span>, ele vitoriosamente
                    <span class="font-bold">voltou à vida!</span> Jesus continua
                    vivo e, ainda hoje, você pode não apenas conhecer mais sobre
                    ele, mas <span class="font-semibold">conhecer a ele</span>.
                    Venha e experimente uma
                    <span class="font-bold">transformação real</span>!
                </p>
            </div>
        </div>
    </div>

    <!-- Bloco de Informações -->
    <div class="w-full mt-8 p-10 bg-[#FFFEF9] text-black py-2">
        <div class="max-w-[1200px] mx-auto">
            <h2 class="text-2xl font-bold mb-4 text-center md:text-left">Informações</h2>
            <p class="text-lg">
                <span class="font-bold">Horários de Culto:</span>
            </p>
            <ul class="list-disc pl-5 text-lg">
                <li>Quintas às 19:30</li>
                <li>Domingos às 19:00</li>
                <li>
                    Primeiros domingos do mês, <span class="font-semibold">Culto de Ceia</span>
                    às 9:00 da manhã
                </li>
                <li>Conheça o nosso blog, Vigilia, lá são postados devocionais, reflexões e nossas
                    programações.
                </li>
            </ul>

            <p class="text-lg mt-4">
                <span class="font-bold">Endereço:</span> Rua Gonçalves Dias, 1214, Centro 
                Campo Largo - PR
            </p>

            <p class="text-lg mt-4">
                <span class="font-bold">Informações de Contato:</span>
            </p>
            <ul class="list-none">
                <li> <i class="fa-solid fa-phone"></i> Telefone: (41) 9 9955-7309 </li>
                <li> <i class="fa-solid fa-envelope"></i> Email: ministerionova@hotmail.com</li>
                <li> <i class="fa-brands fa-whatsapp"></i> WhatsApp: (41) 9 9955-7309 </li>
            </ul>
        </div>
    </div>
</SectionWrapper>
