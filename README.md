# TETRIS

HTML Estrutura: 

Mantivemos a estrutura do HTML intacta, com a tag <canvas> para o jogo Tetris e um elemento <div> para exibir a pontuação.

JavaScript Inicialização: 

O código JavaScript começou com a obtenção do elemento <canvas> e configuração do contexto 2D para desenhar no canvas. A escala do contexto foi ajustada para criar um layout visual do Tetris.

Correções de Funções: 

Várias funções foram corrigidas:

updateScore(); foi adicionado após playerReset(); para atualizar a pontuação.
Corrigimos o uso de updateScore (adicionando parênteses) onde a função é chamada.
Adicionamos update(); para iniciar o loop de atualização do jogo.

Finalização: 

No final do código, definimos o array colors que mapeia cores aos diferentes tipos de peças, criamos a matriz arena para representar o campo de jogo e criamos o objeto player que armazena a posição, a matriz da peça atual e a pontuação. Chamamos playerReset(); para iniciar o jogo e update(); para começar o loop de atualização.

Essencialmente, fizemos pequenas correções, principalmente na chamada de funções e na organização das etapas de inicialização, para garantir que o jogo começasse e funcionasse corretamente. 

CertificamoS de que todas as funções fossem chamadas nos lugares certos para que o jogo pudesse ser executado sem problemas.
