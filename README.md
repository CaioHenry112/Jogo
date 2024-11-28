1. Nomes/RGM/Turma:
         D2 
+ Caio Henrique : 30062314
+ Leonardo Zeraik: 26606151
+ Ricardo Martins Ribeiro: 31306071
+ Yury Moura de Andrade Filho: 29787459
+ Ney Victor: 30220599
+ Yuri Garcia Chacon 30990114
+ Gustavo Borges : 



2. Checklist do DesDenvolvimento do Jogo
Definição do Tema: Escolha e descreva o tema do jogo

- Jogo simulado de fórmula 1 que consiste em se manter na pista sem colidir com ninguém o maior tempo possível.


3. Tecnologias Utilizadas
Liste todas as tecnologias e ferramentas utilizadas no desenvolvimento do jogo, como linguagens de programação, bibliotecas, frameworks, etc.

- Foi usado: HTML, JavaScript.


4. Identificação da Complexidade do Jogo
Descreva a complexidade do jogo, incluindo a análise de algoritmos utilizados.
Explique como a complexidade foi gerenciada durante o desenvolvimento.

- A complexidade consistia em criar um jogo que o carro pudesse correr, freiar e colidir com os outros carros na pista.

- Análise da complexidade do jogo
Algoritmo usado:
Movimento e física do jogo: A lógica de mover um personagem (como um carro em um jogo) pode envolver cálculos físicos simples, como detecção de colisões e atualização da posição do personagem com base no tempo e na velocidade. Algoritmo de movimento: O algoritmo que move o carro pode ser simples, pois atualiza as coordenadas a cada quadro. Isso pode incluir um loop de renderização que atualiza a posição do veículo em cada quadro com base na entrada do jogador (como teclas direcionais) e na física do jogo (como aceleração e fricção). Controle de estradas e obstáculos: estradas e outros objetos dinâmicos (como obstáculos) são animados, possivelmente usando algoritmos que mudam de posição a cada ciclo de atualização. Por exemplo:
Movimento do caminho: pode ser controlado por meio de loops que movem os elementos do fundo e criam a ilusão de movimento contínuo. Detecção de colisão: Algoritmos de colisão simples (como AABB ou colisão circular) podem ser usados ​​para verificar se o veículo atingiu um obstáculo ou limite da estrada.
- Gerenciamento de dificuldades durante o desenvolvimento
Melhorias de desempenho:
Usando animações dinâmicas: O uso de animações CSS (por exemplo, transições, @keyframes) permite um controle refinado sobre a apresentação de elementos visuais. Isso pode reduzir a carga da CPU porque o navegador pode otimizar animações feitas com CSS em vez de realizar cálculos constantes em JavaScript. Evite recalcular a posição do jogo a cada quadro: em vez de atualizar a visualização inteira em cada ciclo de renderização, apenas os elementos que mudam (como posições de veículos ou blocos em movimento) são atualizados. Estratégia de aceleração:
Carregamento assimétrico de recursos: o código pode ser otimizado para carregar recursos de forma assíncrona (como gráficos e áudio) para garantir a renderização ininterrupta do jogo. Usando imagens pixeladas: As imagens são modificadas para fornecer um estilo visual que economize recursos de exibição (para renderização de imagens: recursos pixelados), o que também pode melhorar a eficiência visual e reduzir a complexidade do desempenho gráfico. Manutenção simples:
Segregação de responsabilidades: O código é projetado para que diferentes elementos do jogo (interface do usuário, estradas, veículos, obstáculos) mudem de forma independente. Isso torna mais fácil manter e adicionar novos recursos sem interromper outras partes do jogo. Utilização de um sistema modular: Embora o código resultante não demonstre explicitamente a modularidade, a organização entre HTML, CSS e JavaScript mostra que a separação entre a lógica do jogo e a GUI facilita o aprimoramento e a implementação de novos recursos.

5. Regras (Jogabilidade)
Detalhe as regras do jogo e como ele deve ser jogado.
Inclua instruções claras para os jogadores. 

- O jogo inicia quando aperta a tecla "C'

- O jogador pode escolher em usar o áudio do jogo ou não apertando a tecla "M"

- E o jogador controla o carro usando as setas do teclado, onde dessa forma ele deve tentar chegar o mais longe possível sem colidir com nenhum outro carro da pista

6. Demo do Jogo por Vídeo
Grave um vídeo de no máximo 5 minutos demonstrando o jogo.
Mostre as principais funcionalidades e a jogabilidade.
Certifique-se de que o vídeo está claro e fácil de entender

link: https://youtu.be/XoZcPTnW5Cw
Uma gameplay melhor: https://youtu.be/6MwtmrhjXXo
