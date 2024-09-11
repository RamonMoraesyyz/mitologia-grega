<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/amazonas.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Amazonas
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            As Amazonas, na mitologia grega, eram uma tribo de mulheres guerreiras conhecidas por sua força, coragem e habilidades em combate. Originárias da região da Cítia, às margens do Mar Negro, elas formavam uma sociedade matriarcal onde os homens tinham papéis secundários.

            <p class="mb-2 text-xl">
              Entre as Amazonas mais famosas, destaca-se Hipólita, rainha das Amazonas. Ela possuía um cinturão mágico dado por seu pai, Ares, o deus da guerra. O nono trabalho de Hércules consistia em obter esse cinturão, o que levou a um confronto épico entre o herói e as Amazonas.

              Pentesileia, outra rainha Amazona, liderou suas tropas na Guerra de Troia para ajudar os troianos. Ela foi morta em combate por Aquiles, que se apaixonou por ela ao remover seu elmo e ver sua beleza.
            </p>
            <p class="mb-2 text-xl">
              Antíope, irmã de Hipólita, foi raptada por Teseu e levada para Atenas, onde se tornou sua esposa. Este evento desencadeou uma guerra entre as Amazonas e os atenienses, conhecida como Amazonomaquia.

              As Amazonas eram famosas por suas habilidades com o arco e flecha, e diz-se que removiam um seio para facilitar o uso do arco. Elas também eram excelentes cavaleiras e lutadoras corpo a corpo.

              O mito das Amazonas inspirou inúmeras obras de arte e literatura ao longo da história, e continua a fascinar o imaginário popular até os dias de hoje.
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