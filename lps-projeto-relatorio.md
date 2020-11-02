# Relatório de Desenvolvimento

Entende-se por processo, como uma forma sistemática de se produzir algo. No caso de desenvolvimento de software, ele define uma sequência de atividades que, ao serem realizadas, produzem uma aplicação (IEEE).

## Preocupações

### Tabuleiro
Dado 2~12

Tabela representa o tabuleiro será 12x12, . Os quadros podem estar ocupados (indicado pela letra do nome do personagem) ou vazio (indicado com a letra 'x'). Cada célula deve conter apenas 1 jogador por vez.

Determinados conjuntos de pares ordenados serão nomeados como "Bairro", segue os conjuntos de pares com seus denominados títulos:

Brasilândia {(0,0)(0,1)(0,2)(1,0)(1,1)(1,2)(2,0)(2,1)(2,2)}

Osasco  {(0,9)(0,10)(0,11)(1,9)(1,10)(1,11)(2,9)(2,10)(2,11)}

Taboão  {(9,9)(9,10)(9,11)(10,9)(10,10)(10,11)(11,9)(11,10)(11,11)}

Santana  {(4,4)(4,5)(4,6)(5,4)(5,5)(5,6)(6,4)(6,5)(6,6)}

Sé  {(8,0)(8,1)(9,0)(9,1)(10,0)(10,1)(11,0)(11,1)}

Cotia  {(9,3)(9,4)(9,5)(10,3)(10,4)(10,5)(11,3)(11,4)(11,5)}




|      | 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   | 11   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 0    |   B   |   B   |   B   |      |  o    |      |      |      |   Se   |   Se   |   Se   |   Se   |
| 1    |   B   |   B   |   B   |      |      |      |      |      |   Se   |    Se  |    Se  |   Se   |
| 2    |   B   |   B   |   B   |      |      |      |      |      |      |      |      |   o   |
| 3    |      |      |      |      |      |      |      |      |      |   C   |   C   |   C   |
| 4    |  o    |      |      |      |   Sa   |   Sa   |   Sa   |      |    |    C  |    C  |   C   |
| 5    |      |      |      |      |   Sa   |   Sa   |   Sa   |      |      |   C   |   C   |  C    |
| 6    |      |      |      |      |   Sa   |   Sa   |   Sa   |      |      |      |      |      |
| 7    |      |      |      |      |      |      |      |      |      |      |      |    o  |
| 8    |      |      |      |      |      |      |      |      |      |      |      |      |
| 9    |   O   |   O   |   O   |      |      |      |      |      |      |   T   |   T   |   T   |
| 10   |   O   |   O   |    O  |      |      |      |      |      |      |   T   |   T   |   T   |
| 11   |   O   |   O   |     O |      |    o  |      |      |      |  o    |   T   |   T   |   T   |

Para cada jogador será sorteado um personagem (indicado por 'o' na tabela), os personagens tem posição fixa no tabuleiro para começar o jogo, esses são:

Wesley do grau {(4,0)}

Cleitinho cachorro louco {(11,2)}

Zé corta giro {(0,4)}

Ariane arranca retrovisor {(4,11)}

Wellington do pisca {(11,7)}

Jorginho queixo de para choque {(8,11)}

Para movimentar-se o jogador deve rolar os dados que podem assumir os valores de 2..12, após ser sorteado ele deverá indicar o quadrado adjacente que deseja ocupar até que tenha andado o número de vezes igual sorteado.


### Cartas
Existem no total 18 cartas, 6 representando os personagens, 6 representando veículos e 6 representando os bairros. Essas serão sorteadas entre a quantidade de jogadores.
### Palpite
Para realizar um palpite o jogador devera estar em uma celula de um bairro, devera selecionar 1 personagem, 1 veiculo e 1 bairro, o sistema então indicara quais ṕalpites estão errados para cada categoria.(SE ACERTAR GANHA?)
### Acusar
Para realizar uma acusação o jogador devera estar em uma celula de um bairro, devera selecionar 1 personagem, 1 veiculo e 1 bairro, o sistema então indicara quais ṕalpites estão errados para cada categoria, caso alguma das opções esteja errada o jogador automaticamente perdera o jogo.

## Análise (Problema)

## Desenho (Solução Lógica)

## Implementação (Solução Física)

## Teste (Verificação e Validação)

## Bibliografia

