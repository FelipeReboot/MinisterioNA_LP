<!-- o componente header contem informações imediatas sobre a pagina juntamente
 com a sessão "quem somos", menu que se torna dinamico com o scroll, disponibilizando acesso
 a outras sessões da pagina e links relacionados importantes. -->
<!-- O script importa o menu que abre e fecha da sessão layout para que elas estejam
  devidamente integradas -->

<script>
    import { openModal } from "../Store";
</script>

<header class="flex flex-col relative z-20">
    <div
        class="max-w-[1400px] mx-auto w-full flex
    items-center justify-between p-4 py-6"
    >
        <a href="/">
            <h1 class="font-semibold">
                Ministério <span class="text-[#32746D]">Nova Aliança</span>
            </h1>
            <!--"logo"-->
        </a>
        <!--Abaixo um menu de navegação responsivo com abre e fecha
        para telas pequenas-->
        <button
            on:click={() => ($openModal = true)}
            class="md:hidden grid place-items-center bg-[#FFFEF9]"
        >
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a
                href="#" on:click={(event) => {
                    event.preventDefault(); // Previne o comportamento padrão do link
                    alert('O Blog ainda não esta disponível para acesso');}}
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Vigília</a
            >
            <a
                href="#Missao"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Nossa Missão</a
            >
            <a
                href="#Levando"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Levando Amor</a
            >
            <a
                href="#Contato"
                class="duration-200 hover:text-indigo-400 cursor-pointer"
                >Respostas</a
            >
        </nav>
    </div>
</header>
