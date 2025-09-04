# Matrizes

## 1 - Algoritmo da Mega-Sena

A Mega-Sena é uma das loterias mais conhecidas do Brasil. Nela, são sorteados **6 números diferentes entre 1 e 60**. O jogador também escolhe 6 números, e ganha prêmios de acordo com a quantidade de acertos.

Sua tarefa é desenvolver um programa em linguagem C que:

1. **Gere aleatoriamente 6 números da Mega-Sena**, utilizando a função `rand()` com o intervalo de 1 a 60.

   * Use `srand(time(NULL))` para garantir que a cada execução os números sorteados sejam diferentes.
2. **Defina uma aposta fixa (fezinha)** com 6 números de sua escolha armazenados em um vetor.
3. Mostre na tela:

   * Os 6 números sorteados da Mega-Sena.
   * Os 6 números da sua fezinha.
4. Compare os dois vetores e informe:

   * Quais números da aposta foram sorteados (se houver).
   * A quantidade total de acertos.
5. Caso nenhum número seja igual, o programa deve exibir `0` como números iguais.

**Exemplo de saída esperada (a saída real mudará a cada execução):**

```
=== Numeros da Megasena! ===
10 42 55 2 19 33 

=== Fezinha ===
3 12 23 55 10 42 

Numeros iguais: 10 42 55 
Acertos: 3
```

## 2 – Somando elementos de uma matriz
Um banco quer somar todos os valores de uma matriz 2x3 que representa o valor arrecadado por 2 agências em 3 dias. Imprima o total arrecadado.

Exemplo de saída:
```
Agencia 1, Dia 1: 1890
Agencia 1, Dia 2: 12000
Agencia 1, Dia 3: 7000
Agencia 2, Dia 1: 976
Agencia 2, Dia 2: 123
Agencia 2, Dia 3: 80

Total arrecadado: R$22069
```

## 3 – Média por linha
Registre as notas de 3 alunos em 4 provas. Depois, calcule e exiba a média de cada aluno.

Exemplo de saída:
```
Aluno 1, Prova 1: 10
Aluno 1, Prova 2: 9.5
Aluno 1, Prova 3: 7
Aluno 1, Prova 4: 5.5

Media do aluno 1: 8.00

Aluno 2, Prova 1: 9
Aluno 2, Prova 2: 7.5
Aluno 2, Prova 3: 8.5
Aluno 2, Prova 4: 9

Media do aluno 2: 8.50

Aluno 3, Prova 1: 10
Aluno 3, Prova 2: 7.5
Aluno 3, Prova 3: 3.5
Aluno 3, Prova 4: 2.5

Media do aluno 3: 5.88
```

## 4 – Soma da diagonal principal
Dada uma matriz 4x4, exiba a soma da diagonal principal.

Exemplo de saída:
```
Soma da diagonal principal: 34
```

## 5 – Transposta de uma matriz
Dada uma matriz 3x2, imprima a sua transposta (2x3).

Exemplo de saída:
```
Digite os 6 valores da matriz 3x2 (linha por linha):
Elemento [0][0]: 10
Elemento [0][1]: 12
Elemento [1][0]: 8
Elemento [1][1]: 7
Elemento [2][0]: 19
Elemento [2][1]: 20

Matriz original:

|  10  12 |
|   8   7 |
|  19  20 |

Matriz transposta:

|  10   8  19 |
|  12   7  20 |
```

## 6 – Verificação de matriz identidade
Uma matriz identidade é uma matriz quadrada onde os elementos da diagonal principal são 1 e os demais são 0. Escreva um programa que leia uma matriz 4x4, diga se ela é uma matriz identidade e exiba a matriz formatada.

Exemplo:
```
Matriz identidade? SIM

  1   0   0   0
  0   1   0   0
  0   0   1   0
  0   0   0   1
```