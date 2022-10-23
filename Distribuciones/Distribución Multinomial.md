### Definición
---
La variable aleatoria Multinomial modela la cnatidad de observaciones de cada resultado posible al repetir $n$ veces de forma independiente un experimento que toma valores en $\Set{1, \cdots, k}$ con probabilidades $p_i$ para cada resultado $i \in \Set{1, \cdots, k}$

Se dice que una [[Vector aleatorio]] $X = (X_1, X_2, \cdots, X_k)$ tiene distribución Multinominal de parametros $n$ y $p_1, p_2, \cdots, p_k$ si su [[Función de probabilidad conjunta]] es $$ p_X(x_1, x_2, \cdots, x_k) = \frac{n!}{x_1! \cdot x_2! \cdots x_k!} \cdot p_1^{x_1} \cdot p_2^{x_2} \cdots p_k^{x_k} $$

##### Notación
$$ X \sim M(n, p_1, p_2, \cdots, p_k) $$

#### Notas
---
* El [[Rango de un vector|Rango]] de $X$ es $R_X = \set{ x \in \Set{0, 1, 2, \cdots, n}^k, \displaystyle\sum_{i = 1}^{k} x_i = n}$.
* $\displaystyle{\sum_{i = 1}^{k} p_i = 1}, n \in \mathbb{N}$.
* La [[Esperanza]] es $E[X_i] = n \cdot p_i$, la [[Varianza]] es $Var(X_i) = n \cdot p_i \cdot (1 - p_1)$ y su [[Covarianza]] es $Cov(X_i, X_j) = \begin{cases} Var(X_i) & i = j \\ -n \cdot p_i \cdot p_j & i \ne j \end{cases}$.

### Observaciones
---
* Se tiene que para cada una de las variables aleatorias que componen al vector, sus distribuciones marginales estan dadas por $$ X_i \sim B(n, p_i) $$ una [[Distribución Binomial]].

* El vector aleatorio condicionado por $X_1 = x_1$ tiene distribución $$ (X_2, X_3, \cdots, X_k)|X_1 = x_1 \sim M\bigg(n - x_1, \frac{p_2}{1 - p_1}, \frac{p_3}{1 - p_1}, \cdots, \frac{p_k}{1 - p_1}\bigg) $$