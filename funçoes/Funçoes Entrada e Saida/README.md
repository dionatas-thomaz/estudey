
 # printf(): 

Função usada para imprimir texto na saída padrão (normalmente o console)

### Exemplo:


```c

#include <stdio.h>
int main() {
    printf("Olá, mundo!\n");
    return 0;
}

```


# scanf():

Usado para ler dados da entrada padrão (normalmente o teclado)

### Exemplo:


```c

#include <stdio.h>
int main() {
    int num;
    printf("Digite um número: ");
    scanf("%d", &num);
    printf("Você digitou: %d\n", num);
    return 0;
}

```
