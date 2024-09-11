<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/troia.jfif" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Cidade de Troia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            A cidade de Tróia, também conhecida como Ílion (ou Ilion, em grego), tem suas raízes na antiga região da Ásia Menor, próxima ao estreito de Dardanelos, onde hoje se localiza a Turquia. Sua fundação remonta a tempos pré-históricos, e a cidade desenvolveu-se como uma importante fortaleza e centro de comércio, devido à sua localização estratégica entre o mar Egeu e a Ásia. Acredita-se que a cidade tenha passado por várias reconstruções, conhecidas como diferentes "Troias" arqueológicas, com camadas sucessivas de civilizações construídas sobre as ruínas das anteriores.

            A Tróia mais famosa é a da Guerra de Troia, descrita na mitologia grega e imortalizada por Homero em suas obras Ilíada e Odisseia. Segundo a lenda, essa guerra foi desencadeada quando Páris, um príncipe troiano, sequestrou Helena, a esposa de Menelau, rei de Esparta. Para resgatá-la, Agamenon, irmão de Menelau e rei de Micenas, reuniu uma coalizão de cidades gregas e lançou um ataque contra Tróia. Essa guerra teria durado cerca de dez anos.




            

            <p class="mb-2 text-xl">
                A narrativa central da Guerra de Troia é marcada por figuras heroicas como Aquiles, Heitor, Ajax e Odisseu. Heitor, príncipe troiano e maior guerreiro da cidade, foi um dos principais defensores de Tróia, enquanto Aquiles foi o maior herói grego. A guerra terminou com o famoso episódio do Cavalo de Tróia: os gregos fingiram recuar, deixando para trás um enorme cavalo de madeira como presente. Os troianos, acreditando ser um tributo dos inimigos derrotados, trouxeram o cavalo para dentro de suas muralhas, sem saber que dentro dele estavam soldados gregos. Durante a noite, esses soldados saíram e abriram os portões da cidade, permitindo que os gregos entrassem e destruíssem Tróia.











            </p>
            <p class="mb-2 text-xl">
                Tróia também enfrentou outras guerras e invasões ao longo dos séculos, mas sua destruição pela coalizão grega é a mais famosa. A arqueologia revela que a cidade foi atacada várias vezes e reconstruída, o que sugere que foi um alvo de conflitos por longos períodos de sua história, embora a precisão histórica da Guerra de Troia de Homero ainda seja debatida.

                Uma curiosidade sobre Tróia é que, durante muito tempo, sua existência foi considerada puramente mítica, até que o arqueólogo alemão Heinrich Schliemann, em meados do século XIX, localizou suas ruínas no local agora conhecido como Hisarlik. As escavações de Schliemann revelaram várias camadas de cidades sobrepostas, confirmando que Tróia não era apenas uma lenda, mas um local real que passou por diferentes civilizações ao longo dos milênios.






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