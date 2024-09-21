<script>
  //Importa aruivo css global 
  import "../app.css";
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import { openModal } from "../Store";

  //função que redireciona para um componente e fecha o menu
  let y;
  $: outerHeight = 0;

  function reroute(href) {
    $openModal = false;
    window.location.href = href;
  }
</script>

<!--Exibe o menu de navegaçao para telas pequenas, cada um dos links recebe uma
estilização e é responsivo e dinamico-->
{#if $openModal}
  <div
    class=" fixed top-0 left-0 w-screen h-screen
  border-b bg-[#FFFEF9] z-50 flex flex-col gap-8 p-5 px-8 md:hidden"
  >
    <div class="flex items-center justify-between gap-4 border-b pb-2">
      <h1 class="font-semibold">
        Ministério <span class="text-[#32746D]">Nova Aliança</span>
      </h1>
      <button
        on:click={() => ($openModal = false)}
        class="outline-none border-none"
      >
        <i class="fa-solid fa-xmark text-2xl"></i>
      </button>
    </div>
    <div class=" flex flex-col gap-4">
      <!--O primeiro botão direciona para o blog, os demais para sessoes da pagina-->
      <button
        on:click={() => reroute("/")}
        class=" bg-[#FFFEF9] boder-none outline-none p-2 group duration-200 cursor-pointer
      text-left"
      >
        <p
          class="duration-200 group-hover:pl-2 poppins text-2xl
        font-semibold"
        >
          Vigilia<i class="fa-solid fa-chevron-right text-lg pl-4" />
        </p>
      </button>
      <button
        on:click={() => reroute("#Missao")}
        class=" bg-[#FFFEF9] boder-none outline-none p-2 group duration-200 cursor-pointer
    text-left"
      >
        <p
          class="duration-200 group-hover:pl-2 poppins text-2xl
      font-semibold"
        >
          Nossa Missão<i class="fa-solid fa-chevron-right text-lg pl-4" />
        </p>
      </button>

      <button
        on:click={() => reroute("#Levando")}
        class=" bg-[#FFFEF9] boder-none outline-none p-2 group duration-200 cursor-pointer
text-left"
      >
        <p
          class="duration-200 group-hover:pl-2 poppins text-2xl
  font-semibold"
        >
          Levando Amor<i class="fa-solid fa-chevron-right text-lg pl-4" />
        </p>
      </button>

      <button
        on:click={() => reroute("#Contato")}
        class=" bg-[#FFFEF9] boder-none outline-none p-2 group duration-200 cursor-pointer
text-left"
      >
        <p
          class="duration-200 group-hover:pl-2 poppins text-2xl
font-semibold"
        >
          Respostas<i class="fa-solid fa-chevron-right text-lg pl-4" />
        </p>
      </button>
    </div>
  </div>
{/if}

<!--Header fixo com o scroll, dinamico e responsivo-->
{#if y > outerHeight}
  <div
    class="bg-[#FFFEF9] fixed top-0 left-0 w-full flex flex-col z-20 px-4 fadeIn"
  >
    <Header />
  </div>
{/if}

<slot />
<Footer />
<svelte:window bind:scrollY={y} bind:outerHeight />
<!-- header+quem somos
nossa missao
levando amor
Respostas
footer -->
