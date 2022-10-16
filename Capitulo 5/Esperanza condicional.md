	### Definición
---
Definimos a la [[Variable aleatoria]] esperanza condicinal de $Y$ dado $X$, denotada por $E[Y|X]$, como la [[Función de regresión]] evaluado en $X$ de forma que $$ \varphi(X) = E[Y|X] $$
#### Propiedades
---
* La [[Esperanza]] de la "esperanza condicional de $Y$ dado $X$" es la [[Esperanza]] de $Y$ $$ E[E[Y|X]] = E[Y] $$
* Sean $X$ e $Y$ variables aleatorias, $s$ y $r$ funciones medibles tales que las variables aleatorias $r(X) \cdot s(Y)$, $r(X)$ y $s(Y)$ tienen esperanza fininta. Entonces $$ E[r(X) \cdot s(Y)|X] = r(X) \cdot E[s(Y)|X] $$
* Sean $Y_1$ e $Y_2$ variables aleatorias con esperanza finita. Entonces $$ E[a \cdot Y_1 + b Y_2 | X] = a \cdot E[Y_1| X] + b \cdot E[Y_2| X] $$
* $X$ e $Y$ son [[Variables independientes]] si $E[Y|X] = E[Y]$
* $E[r(X)|X] = r(X)$

### Observación
---
* La esperanza condicional siempre existe, y además es única con probabilidad $1$.
* Es la función que mejor predice a $Y$.
* Si $E[Y|X]$ es una función de $X$ y esta es lineal, esta coincide con la [[Recta de regresión]].