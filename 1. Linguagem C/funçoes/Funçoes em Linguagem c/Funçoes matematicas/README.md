## Funções Matemáticas:

C oferece uma variedade de funções matemáticas, como:
```c
sqrt(), pow(), sin(), cos(), etc.
```
Essas funções estão disponíveis na biblioteca padrão de C, que é chamada de`<math.h>`. Aqui estão algumas das funções matemáticas mais comuns disponíveis em C:
 

`sqrt()`: Calcula a raiz quadrada de um número.

```c
#include <math.h>
double resultado = sqrt(25.0); 
    // resultado é 5.0
```

`pow()`: Calcula a potência de um número.

```c
#include <math.h>
double resultado = pow(2.0, 3.0);
     // resultado é 8.0 
```
`sin()`: Calcula o seno de um ângulo em radianos.

```c

#include <math.h>
double resultado = sin(1.5708);
// resultado é 1.0 (seno de 90 graus) 
```
`cos()`: Calcula o cosseno de um ângulo em radianos.

```c
#include <math.h>
double resultado = cos(0.0);
// resultado é 1.0 (cosseno de 0 graus) 
```
`tan()`: Calcula a tangente de um ângulo em radianos.

```c
#include <math.h>
double resultado = tan(0.7854);
// resultado é 1.0 (tangente de 45 graus) 
```
`log()`: Calcula o logaritmo natural (base e) de um número.

```c
#include <math.h>
double resultado = log(2.7183);
// resultado é aproximadamente 1.0 
```
`log10()`: Calcula o logaritmo na base 10 de um número.

```c
#include <math.h>
double resultado = log10(100.0);
     // resultado é 2.0 
```
`fabs()`: Retorna o valor absoluto de um número.

```c
#include <math.h>
double resultado = fabs(-5.0);
    // resultado é 5.0 
```
`ceil()`: Arredonda um número para cima para o inteiro mais próximo.

```c
#include <math.h>
double resultado = ceil(4.3);
    // resultado é 5.0 
```
`floor()`: Arredonda um número para baixo para o inteiro mais próximo.

```c
#include <math.h>
double resultado = floor(4.9);
   // resultado é 4.0 
```
Essas são apenas algumas das funções matemáticas disponíveis em C. A biblioteca math.h oferece muitas outras funções úteis para cálculos matemáticos complexos. Certifique-se de incluir #include `<math.h>` no início do seu programa para usar essas funções.