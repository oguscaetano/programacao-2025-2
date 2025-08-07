# Introdução a Programação

## Introdução à Programação e Algoritmos
- O que é programação?
  - Programação é o processo de escrever instruções que um computador pode entender e executar.
  - Analogia: Assim como uma receita de bolo tem passos que devem ser seguidos na ordem correta, um programa de computador é um conjunto de instruções para realizar uma tarefa.

- O que são algoritmos?
  - Um algoritmo é uma sequência de passos bem definidos para resolver um problema.
  - Exemplo prático: Vamos criar um algoritmo para preparar uma caneca de chocolate quente. 
    - Passo 1: Pegar uma caneca
    - Passo 2: Pegar o leite
    - Passo 3: Esquentar o leite 
    - Passo 4: Colocar leite quente na caneca  
    - Passo 5: Adicionar o chocolate em pó  
    - Passo 6: Misturar  
    - Passo 7: Beber  

## O que é a Linguagem C?
- Criada por **Dennis Ritchie** em **1972**.  
- Base para várias outras linguagens (C++, Java, Python).  
- **Linguagem de alto desempenho** e utilizada em sistemas operacionais, jogos e embarcados.  

## Escrevendo e Rodando um Programa em C
Agora, vamos testar se tudo está funcionando:
 
Escreva o seguinte código:

   ```c
   #include <stdio.h>

   int main() {
       printf("Ola, Mundo!\n");
       return 0;
   }
   ```

📌 **Explicação:**  
- `#include <stdio.h>` → Biblioteca para entrada e saída.  
- `int main()` → Função principal do programa.  
- `printf("Ola, Mundo!\n");` → Imprime texto na tela.  
- `return 0;` → Indica que o programa finalizou corretamente.

## Variáveis
- O que são variáveis?
  - Uma variável é um espaço na memória do computador onde podemos armazenar um valor.
  - Analogia: Pense em uma variável como uma caixinha onde guardamos algo, como um número ou um nome.

## Tipos de Dados em C
| Tipo         | Tamanho (bytes) | Faixa de Valores (Aproximada) | Exemplo de Uso |
|-------------|----------------|---------------------------------|----------------|
| `char`      | 1 byte         | -128 a 127 (`signed char`)<br>0 a 255 (`unsigned char`) | `char letra = 'A';` |
| `int`       | 4 bytes        | -2.147.483.648 a 2.147.483.647 | `int idade = 25;` |
| `float`     | 4 bytes        | ~6 casas decimais de precisão | `float pi = 3.1415;` |
| `double`    | 8 bytes        | ~15 casas decimais de precisão | `double numero = 2.718281828;` |

## Declarando variáveis
É dessa forma que declaramos variáveis, atribuímos valores a elas e exibimos na tela (`printf()`).

```c
#include <stdio.h>

int main() {
    char letra = 'A';
    int idade = 25;
    float pi = 3.1415f;
    double numero = 2.718281828;

    printf("char: %c\n", letra);
    printf("int: %d\n", idade);
    printf("float: %.4f\n", pi);
    printf("double: %.9f\n", numero);

    return 0;
}
```

## Operadores Matemáticos
Operadores matemáticos são símbolos usados para realizar operações como `soma`, `subtração`, `multiplicação` e `divisão`.

| Operador | Operação        | Exemplo       | Resultado |
|----------|----------------|--------------|-----------|
| `+`      | Adição         | `5 + 3`      | `8`       |
| `-`      | Subtração      | `10 - 4`     | `6`       |
| `*`      | Multiplicação  | `2 * 6`      | `12`      |
| `/`      | Divisão        | `10 / 4`     | `2.5`     |
| `%`      | Resto da divisão (módulo) | `10 % 4`  | `2`       |

Exemplo:
```c
int soma = 5 + 3;
int produto = 5 * 3;
```

## Precedência de Operadores
Assim como na matemática, as operações seguem uma ordem de precedência:

1. **Parênteses `()`** → Tem a maior prioridade.
2. **Multiplicação `*`, Divisão `/`, Módulo `%`** → Vêm antes da adição e subtração.
3. **Adição `+` e Subtração `-`** → São as últimas a serem resolvidas.
