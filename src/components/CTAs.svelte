<script>
    import Contato from "./Contato.svelte";

     // Função para rolar suavemente até a seção de "Contato"
     function scrollToContato() {
        document.getElementById('Contato').scrollIntoView({ behavior: 'smooth' });
    }
   
</script>

<div class="flex items-center justify-center gap-4">
    <!-- Botão de "call to action", para acesso direto à sessão de "conversão" -->
    <button class="specialBtnDark" on:click={scrollToContato}>
        <p class="text-base sm:text-lg md:text-xl">Encontre perdão &#10013</p>
    </button>
</div>