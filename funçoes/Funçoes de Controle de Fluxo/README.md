## If, Else: 
<BR>
Essas estruturas de controle condicional são usadas para tomar decisões com base em uma condição. O programa verifica se uma condição é verdadeira (if) ou falsa (else) e executa blocos de código diferentes com base nessa avaliação.

<BR>

```C
#include <stdio.h>

int main() {
    int numero = 10;

    if (numero > 5) {
        printf("O número é maior que 5.\n");
    } else {
        printf("O número não é maior que 5.\n");
    }

    return 0;
}
```
<BR>

## Switch, Case: 
A estrutura de controle switch é usada para realizar seleções múltiplas com base no valor de uma expressão. Ela permite que você compare o valor de uma expressão com diferentes casos e execute o código correspondente ao caso que corresponda ao valor da expressão.

<BR>

```C
#include <stdio.h>

int main() {
    char op;
    printf("escolha uma op: 1 , 2 , 3 ");
    scanf("%c",&op);

    switch (op) {
        case 1:
            printf("Opção 1 selecionada.\n");
            break;
        case 2:
            printf("Opção 2 selecionada.\n");
            break;
        case 3:
            printf("Opção 3 selecionada.\n");
            break;
        default:
            printf("Opção não reconhecida.\n");
    }

    return 0;
}
```
<BR>

## While, Do While, For: 
Essas são estruturas de controle de loop que permitem que você execute um bloco de código repetidamente. O while é usado quando você deseja repetir um bloco de código enquanto uma condição for verdadeira. O for é usado quando você deseja executar um bloco de código um número específico de vezes ou percorrer uma sequência, como uma lista ou uma matriz.

<BR>

## While

```c
#include <stdio.h>

int main() {
    int contador = 0;

    while (contador < 5) {
        printf("Contador: %d\n", contador);
        contador++;
    }

    return 0;
}
```
<br>

## Do While

```c
#include <stdio.h>

int main() {
    int contador = 0;

    do {
        printf("Contador: %d\n", contador);
        contador++;
    } while (contador < 5);

    return 0;
}
```
<br>

## For

```c
#include <stdio.h>

int main() {
    for (int i = 0; i < 5; i++) {
        printf("Iteração: %d\n", i);
    }

    return 0;
}
```