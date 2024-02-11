
# Operadores Lógicos em JS

### Os operadores lógicos são essenciais na programação para realizar comparações e tomar decisões com base nos resultados dessas comparações.

<br>

- - - - 

```javascript:main.js
let num = 123;
if (num == 123) {} // verdadeiro
```
Explicação: O operador `==` compara dois valores e retorna verdadeiro se eles forem iguais após a coerção de tipo. Neste caso, num é um número e 123 também é um número, então a comparação avalia como verdadeira.

- - - - 

```javascript:main.js
let num = 123;
if (num === "123") {} // falso
```
Explicação: O operador `===` compara dois valores estritamente, sem coerção de tipo. Neste caso, num é um número e `"123"` é uma string, então eles não são estritamente iguais, resultando em falso.

- - - - 

```javascript:main.js
let num = 123;
if (num != 456) {} // verdadeiro
```
Explicação: O operador `!=` retorna verdadeiro se os operandos não forem iguais após a coerção de tipo. Aqui, num é 123 e 456 não é igual a 123, então a comparação é verdadeira.

- - - - 

```javascript:main.js
let num = 123;
if (num !== "123") {} // verdadeiro
```
Explicação: O operador `!==` retorna verdadeiro se os operandos não forem iguais sem coerção de tipo. Neste caso, num é um número e `"123"` é uma string, então eles não são estritamente iguais, resultando em verdadeiro.

- - - - 

```javascript:main.js
let num = 123;
if (num > 100) {} // verdadeiro
```
Explicação: O operador `>` retorna verdadeiro se o operando da esquerda for maior que o da direita. Aqui, num (123) é maior que 100, então a comparação é verdadeira.

- - - - 

```javascript:main.js
let num = 123;
if (num < 200) {} // verdadeiro
```
Explicação: O operador `<` retorna verdadeiro se o operando da esquerda for menor que o da direita. Neste caso, num (123) é menor que 200, então a comparação é verdadeira.

- - - - 

```javascript:main.js
let num = 123;
if (num >= 123) {} // verdadeiro
```
Explicação: O operador `>=` retorna verdadeiro se o operando da esquerda for maior ou igual ao da direita. Aqui, num (123) é igual a 123, então a comparação é verdadeira.

- - - - 

```javascript:main.js
let num = 123;
if (num <= 200) {} // verdadeiro
```
Explicação: O operador `<=` retorna verdadeiro se o operando da esquerda for menor ou igual ao da direita. Neste caso, num (123) é menor que 200, então a comparação é verdadeira.

- - - - 

```javascript:main.js
let a = true;
let b = false;
if (a && b) {} // falso
```
Explicação: O operador `&&` retorna verdadeiro se ambos os operandos forem verdadeiros. Neste caso, como `a` é verdadeiro e `b` é falso, o resultado é falso.

- - - - 

```javascript:main.js
let a = true;
let b = false;
if (a || b) {} // verdadeiro
```
Explicação: O operador `||` retorna verdadeiro se pelo menos um dos operandos for verdadeiro. Neste caso, como `a` é verdadeiro, o resultado é verdadeiro.

- - - - 

```javascript:main.js
let a = true;
if (!a) {} // falso
```
Explicação: O operador `!` retorna a negação lógica de seu operando. Neste caso, `a` é verdadeiro, então `!a` é falso.






