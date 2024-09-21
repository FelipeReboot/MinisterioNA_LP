<footer class="py-16 sm:py-20 md:py-24 px-4 md:px-8 bg-[#32746D]"> <!-- footer simples -->
    <div
        class="max-w-[1200px] mx-auto w-full grid grid-cols-1
    sm:grid-cols-2 md:grid-cols-5 gap-8 text-base text-[#FFFEF9]"
    >
        <div class="flex flex-col gap-4 md:col-span-2">
            <h1 class="font-semibold ">
                Ministério <span class="text-[#00000]">Nova Aliança</span> 2024
            </h1>
            <p>imagens de freepik</p> <!-- "logo" da igreja como no header -->
        </div>
        <div class="flex flex-col gap-4">
            <p class="font-bold poppinf text-base sm:text large"> 
                Redes Sociais
            </p>
            <a
                class="cursor-pointer hover:text-indigo-400 duration-200"
                href="#" on:click={(event) => {
                    event.preventDefault(); // Previne o comportamento padrão do link
                    alert('O linktree ainda não está disponivel');}}
                target="_blank"
             
            > <i class="fa-solid fa-tree"></i> Linktree <!-- links que levarão as paginas propostas-->
            </a>
        </div>
        <div class="flex flex-col gap-4">
            <p class="font-bold poppinf text-base sm:text large">
                Receba uma Biblia
            </p>
            <a
                href="#" on:click={(event) => {
                    event.preventDefault(); // Previne o comportamento padrão do link
                    alert('A pagina do projeto semear ainda não está disponivel');}}
                target="_blank"
                class="cursor-pointer hover:text-indigo-400 duration-200"
            > <i class="fa-solid fa-book-bible"></i> Projeto Semear
            </a>
        </div>
        <div class="flex flex-col gap-4">
            <p class="font-bold poppinf text-base sm:text large">
                Nos ajude e ajudar
            </p>
            <a
                href="https://doemna.vercel.app/"
                target="_blank"
                class="cursor-pointer hover:text-indigo-400 duration-200"
            > <i class="fa-solid fa-hand-holding-dollar"></i> Doe
            </a>
        </div>
    </div>
</footer>
