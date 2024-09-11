<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/faetonte.jfif" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Faetonte
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            Faetonte, filho do deus sol Hélio e da oceânide Clímene, é uma figura trágica da mitologia grega. Sua história é um conto de ambição juvenil e as consequências devastadoras da arrogância.

            Crescendo com dúvidas sobre sua paternidade divina, Faetonte decidiu visitar o palácio de seu pai para provar sua linhagem. Hélio, feliz em ver seu filho, prometeu conceder-lhe qualquer desejo como prova de seu amor paterno.

            <p class="mb-2 text-xl">
              Impulsivamente, Faetonte pediu para conduzir o carro solar de seu pai por um dia. Apesar das advertências de Hélio sobre os perigos, o jovem insistiu. Relutantemente, Hélio cedeu ao pedido.

              No entanto, Faetonte logo perdeu o controle dos cavalos divinos. O carro solar desviou-se de seu curso, ora subindo muito alto e congelando a Terra, ora descendo demais e queimando-a. Para evitar uma catástrofe maior, Zeus foi forçado a intervir, fulminando Faetonte com um raio.
            </p>
            <p class="mb-2 text-xl">
              O corpo de Faetonte caiu no rio Erídano, onde suas irmãs, as Helíades, o choraram até se transformarem em álamos.

              Uma curiosidade interessante é que o mito de Faetonte tem sido interpretado como uma alegoria para explicar fenômenos astronômicos e climáticos. Alguns estudiosos sugerem que a história pode ter sido inspirada por eventos reais, como a queda de um meteorito ou mudanças climáticas extremas na antiguidade.
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