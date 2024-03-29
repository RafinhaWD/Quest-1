Encontrar Número Não Repetido em um Array

Este programa Java encontra o número que não se repete em um array de inteiros, 
onde todos os outros números se repetem exatamente três vezes.

Funcionamento do Algoritmo
O algoritmo utiliza operadores bitwise (que seria uma forma mais eficiente de encontrar o numero não repetido usando o XOR (^) e AND (&).

Inicialização de Variáveis: Inicializa duas variáveis, umNum e doisNum ambas com valor 0.

Alterando as Variáveis:
umNum = (umNum ^ num) & ~doisNum;: Atualiza umNum usando a operação XOR e AND.
doisNum = (doisNum ^ num) & ~umNum;: Atualiza usando a mesma operação.

Retorno do Resultado: Retorna o valor de umNum, que contém o número não repetido usando sysout.

Execução do Programa
O programa é executado no método main, colocando uma estrutura array de inteiros como argumento para a função encontrarNumeroNaoRepetido. O resultado é então impresso na tela usando o Sysout.

Como Utilizar
Para utilizar este algoritmo em seu próprio código, copie a função encontrarNumeroNaoRepetido e coloque um valor array de inteiros desejado.