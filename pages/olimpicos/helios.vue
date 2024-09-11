<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/helios.jpg" class="w-full h-full object-cover" />
      </div>

      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hélio
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Hélio é o deus grego personificação do Sol, filho dos titãs Hipérion e Teia, e irmão de Selene, a deusa da Lua, e Eos, a deusa da Aurora. Na mitologia grega, Hélio é descrito como uma figura resplandecente que atravessa os céus todos os dias, conduzindo uma carruagem dourada puxada por cavalos flamejantes. Ele trazia a luz do dia ao mundo, fazendo sua jornada do leste ao oeste, e à noite retornava pelo Oceano para começar o ciclo novamente ao amanhecer.

            Hélio desempenhava um papel crucial na ordem natural do cosmos, sendo venerado como aquele que ilumina a terra e observa tudo que ocorre embaixo. Essa característica de onisciência era importante, pois ele podia testemunhar atos e acontecimentos que outros deuses não viam. Um exemplo notável de seu papel como testemunha foi quando ele revelou a Afrodite e Hefesto a traição de Afrodite com Ares.
            

            <p class="mb-2 text-xl">
                Entre os filhos mais conhecidos de Hélio está Faetonte, que tem uma história trágica. Faetonte, desejando provar sua ascendência divina, pediu ao pai que lhe permitisse conduzir a carruagem do Sol por um dia. Relutante, Hélio concordou, mas o jovem, incapaz de controlar os cavalos flamejantes, fez com que o Sol se aproximasse demais da Terra, causando queimaduras devastadoras. Para evitar uma catástrofe ainda maior, Zeus fulminou Faetonte com um raio, matando-o. Essa lenda explica a criação do deserto do Saara e as diferentes zonas climáticas.

                Hélio também teve vários outros filhos e filhas. Com a ninfa Perseis, ele gerou Circe, a famosa feiticeira, e Eetes, o rei da Cólquida (pai de Medeia). Além disso, suas filhas, conhecidas como as Helíades, choraram tanto pela morte de Faetonte que foram transformadas em choupos, com suas lágrimas se transformando em âmbar.



            </p>
            <p class="mb-2 text-xl">
                Uma curiosidade sobre Hélio é que, com o tempo, ele foi gradualmente substituído por Apolo como o deus associado ao Sol, principalmente na era helenística. Isso não significa que Hélio desapareceu, mas Apolo passou a ser visto como a personificação mais jovem e moderna do Sol, enquanto Hélio permaneceu como uma figura mais arcaica e primordial.

            </p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button
              class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded"
            >
              Menu
            </button>
          </nuxt-link>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .bg-brown-dark {
    background-color: #211512;
  }
  </style>