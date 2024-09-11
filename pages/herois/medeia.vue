<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/medeia.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Medéia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Medeia, uma das figuras mais complexas da mitologia grega, é uma poderosa feiticeira, filha de Eetes, rei da Cólquida, e neta do deus Hélio. Sua história está profundamente entrelaçada com o mito de Jasão e os Argonautas, especialmente a busca pelo Velocino de Ouro.

            Quando Jasão chegou à Cólquida em busca do Velocino, Medeia se apaixonou por ele, graças à intervenção de Afrodite, e decidiu ajudá-lo em sua missão. Usando seus vastos conhecimentos de magia, ela ajudou Jasão a superar os desafios impostos por seu pai, como arar um campo com touros que soltavam fogo pelas narinas e derrotar guerreiros nascidos de dentes de dragão. Após a vitória, Medeia o auxiliou a roubar o Velocino e fugiram juntos para a Grécia.




            

            <p class="mb-2 text-xl">
              Durante sua fuga, Medeia tomou decisões cruéis. Para retardar a perseguição de seu pai, ela matou e esquartejou seu irmão, Absirto, espalhando seus pedaços pelo mar. Isso forçou Eetes a parar e recolher os restos mortais de seu filho.

              Ao chegarem à Grécia, Jasão e Medeia casaram-se e tiveram filhos, mas seu destino foi manchado pela tragédia. Jasão acabou traindo Medeia ao casar-se com Glauce, filha do rei Creonte de Corinto. Em vingança, Medeia usou sua magia para enviar um manto envenenado para Glauce, que a matou, junto com Creonte. Em seu ato final de fúria e desespero, Medeia assassinou seus próprios filhos, Mermeros e Feres, para punir Jasão.




            </p>
            <p class="mb-2 text-xl">
              Após esses eventos, Medeia fugiu para Atenas, onde se casou com o rei Egeu e tentou envenenar seu filho, Teseu, mas foi descoberta e fugiu novamente.

              Uma curiosidade sobre Medeia é que, em algumas versões do mito, ela não mata seus filhos por vingança, mas eles são apedrejados pelos habitantes de Corinto, e essa ação é atribuída a ela como um mito construído para desacreditá-la.










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