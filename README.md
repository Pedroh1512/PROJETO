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
- Prints ChatGPT:
![Chat Gpt 1](https://github.com/user-attachments/assets/1d6dd15c-b1d2-4ee9-b70b-7419b6e4c1ba)
![Chat Gpt 2](https://github.com/user-attachments/assets/b185cf3f-8af9-4d0a-8b01-ca0a65da21d6)
![Chat Gpt 3](https://github.com/user-attachments/assets/c74697da-145d-4af2-8700-3b84d3f98b3f)
![Chat Gpt 4](https://github.com/user-attachments/assets/3636d4be-ae3f-49a9-9d16-d8a06e73f358)
![Chat Gpt 5](https://github.com/user-attachments/assets/f22d892f-cd34-42e9-b234-56f76cf2a2ee)
![Chat Gpt 6](https://github.com/user-attachments/assets/1303fabb-4393-4cd4-b086-b8c5802cd861)
![Chat Gpt 7](https://github.com/user-attachments/assets/307d96b2-2f6e-4628-8c14-a433b9c8ae46)
![Chat Gpt 8](https://github.com/user-attachments/assets/8a922c7d-6949-4b8d-bf4d-425db805a3d0)
![Chat Gpt 9](https://github.com/user-attachments/assets/2ccd4947-8d34-4810-b1fa-a392cb44f510)
![Chat Gpt 10](https://github.com/user-attachments/assets/e4486936-0f50-4a0c-8672-f7dacd673ad5)
![Chat Gpt 11](https://github.com/user-attachments/assets/ca7eccd3-a444-45c1-8be3-ed7859bd7f83)
![Chat Gpt 12](https://github.com/user-attachments/assets/85c22b54-e82e-4b90-b304-15e7fe47d8b1)












