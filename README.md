# Integrantes
- Gustavo Sarquis
- Pedro Henrique

# Jogo
O jogo principal conta com 3 minijogos desenvolvidos e o código do jogo se divide em 4 partes.
No desenvolvimento do jogo foi utilizado 5 bibliotecas:
- <stdio.h>
- <stdlib.h>
- <time.h>
- <string.h>
- <locale.h>

# Menu
A primeira parte do jogo é o menu principal, o qual foi utilizado switch case com quatro opções de case, o primeiro direciona o usuário para o primeiro jogo(Perguntas e Respostas), o segundo case direciona o usuário para o segundo jogo(Cobra na Caixa!), o terceiro case direciona o usuário para o terceiro jogo(Gousmar War), e o último case fecha o jogo, fechando o programa.

# Jogo 1
O primeiro minijogo é o "Perguntas e Respostas", nesse jogo, o usuário deve responder 5 perguntas acerca de temas gerais, as perguntas possuem 4 afirmativas com uma certa, ao final do jogo é mostrado a quantidade de acertos do jogador.
Acerca do desenvolvimento do jogo: Foi ultilizado um laço de repetição (while), com a finalidade de o usuário poder jogar o jogo novamente ou finalizar o minijogo e voltar ao menu principal. Além do laço de repetição, o jogo também apresenta switch case para cada pergunta, cada switch possuí 4 cases, o codigo possuí também um contador, que ao usuário marcar a alternativa certa, aumenta de 1 em 1, e, ao final do jogo, é mostrado o numero de acertos/5.

# Jogo 2
O segundo minijogo é o "Cobra na Caixa!", nesse jogo, são dois jogadores, que, primeiramente, devem escolher seus personagens dentre os 7 predefinidos, após isso, ocorre um sorteio para ver qual usuário vai começar, após o sorteio, o primeiro jogador deve escolher uma caixa dentre as 5 possiveis, 1 possuí uma cobra, que elimina o jogador, 1 possuí um botão, que abre a porta e o usuário ganha, e 3 que não possuem nada, fazendo com que o jogador passe a vez para o outro jogador.
Acerca do desenvolvimento do jogo: Foi utilizado para as opções de personagens predefinidos, o comando string, junstamente à switch case com 7 opções de nomes. Após a escolha dos nomes, ocorre um sorteio para ver qual jogador começará, para isso foi utilizado o comando rand, assim como para o sorteio da caixa, o qual embaralha as caixas e as rodadas, fazendo com que as caixas mudem de posição de um jogo para o outro. Com  a finalidade de ver quem venceu, foi utilizado um if e else, o qual, se o jogador digitar a caixa com o botão, o jogador ganhará, caso o mesmo escolha um caixa sem nada, a rodada passa para o adversário, e se o jogador escolher a caixa com a cobra, ele perderá. Após um jogador ganhar ou  perder, o jogo é finalizado.

# Jogo 3
O terceiro jogo é o "Gousmas war", o jogo precisa de dois jogadores, assim como o 2 jogo. Neste jogo de estratégia, os jogadores controlam criaturas chamadas
Gousmas, que podem se dividir e acumular fúria ao serem atacadas. Cada usuário começa o jogo com duas gousmas, cada uma com um nível de fúria. Ao ataca outro gousma, o que atacou transfere todo o seu nível de fúria ao gousma atacado. O jogador também pode dividir uma gousma, ao dividir sua fúria, respeitando a quantidade mínima de 1 fúria para cada gousma. Se a gousma atingir o nível 5 de fúria ou passra de 5, ela se desintegra. Ao perder as duas Gousmas, o jogador perde a partida.  
Acerca do desenvolvimento do jogo: Foi utilizado para switch case para selecionar as escolhas de cada jogador, selecionando a gousma que se deseja utilizar na jogada, podendo escolher entre atacar ou redistribuir a fúria das gousmas, para simplificar as funções de de redistribuir a fúria, zerar uma gousma, checar a pontuação de cada jogador e de finalizar a partida foram criadas funções usando o void para definir essas funcionalidades, também sendo utilizado o while para alternar entre os jogadores até que a partida se encerre.

# Referências
- DAMAS, Luís. Linguagem C. 10.ed. Rio de Janeiro: LTC, 2007.
- Prints ChatGPT (Publicados nos Anexos da Atividade).

