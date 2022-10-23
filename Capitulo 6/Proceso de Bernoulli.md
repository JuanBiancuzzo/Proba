### Definición
---
Dado varias [[Variable aleatoria|variables aleatorias]] $X_i$ donde $X_i \sim Ber(p)$ una [[Distribución de Bernoulli|distribución de Bernoulli]], donde tiene 
* Una distribución dicotomica, puede salir $1$ o no.
* $\mathbb{P}(X_i = 1) = p$ para toda $i$ ($p$ es constante).
* Los experimentos son [[Variables independientes|independientes]].
Esto se llama proceso de Bernoulli, y $X_i = 1$ se lo llama exito y $p$ la probabilidad del exito.


### Cantidad $n$ de ensayos de Bernoulli
---
Dado la variable $Y$ como la cantidad de exitos en $n$ ensayos de Bernoulli, su [[Rango]] es $R_Y = \Set{0, 1, 2, \cdots, n}$ y vemos que $Y$ tiene una [[Distribución Binomial]], $Y \sim B(n, p)$. Pero notemos que $$Y = \sum_{i = 1}^{n}X_i$$

### Cantidad de ensayos hasta el primer exito
---
Dado la variable $N$ como la cantidad de ensayos de Bernoulli hasta el primer exito, su [[Rango]] es $R_N = \mathbb{N}$ y vemos que $N$ tiene una [[Distribución Geométrica]], $N \sim G(p)$.


### Cantidad de ensayos de Bernoulli con $k$ exitos
---
Dado la variable $W$ como la cantidad de ensayos de Bernoulli hasta lograr $k$ exitos, su [[Rango]] es $R_W = \Set{k, k+1, \cdots}$ y vemos que $W$ tiene una [[Distribución de Pascal]], $W \sim Pas(k, p)$. Pero notemos que $$ W = \sum_{i = 0}^{k} N_i $$ donde $N_i \sim G(p)$ e [[Variables independientes|independientes]] entre si.

