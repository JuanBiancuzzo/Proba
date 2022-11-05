### Definición
---
Dado un [[Proceso puntual]], donde los arribos sean independientes y entre dos arribos consecutivos su distancia tenga [[Distribución exponencial]]. Con la siguiente notación: $$ \Pi \sim PPP(\lambda) $$ donde $\lambda$ es la intensidad o tasa de ocurrencia


### Variables utiles
---
Por lo que vamos a definir las siguientes [[Variable aleatoria|variables aleatorias]]. 

Definimos como $N(a, b)$  a la cantidad de arribos entre $a$ y $b$, donde $a < b$. Esta variable tiene [[Distribución de Poisson]], $N(a, b) \sim Poi(\mu = \lambda \cdot (b - a))$. Por convención de notación diremos que $N(0, t) \equiv N(t)$.

Definimos a las variables $G_n$ como el tiempo hasta el $n$-esimo arribo. Donde cumplen que tienen [[Distribución Gamma]], $G_n \sim \Gamma(n, \lambda)$.

Definimos las variables $T_{i,j}$ como el tiempo entre dos arribos consecutivos, el $i$-esimo y el $j$-esimo. Entonces son $T_{i, j} = G_j - G_i \sim \varepsilon(\lambda)$ pero por convención llamaremos $T_i$ donde cumple $T_i = G_i - G_{i - 1}$ y definimos $G_0$ como $0$.


### Propiedades
---
* $$ \mathbb{P}(G_n > t) = \mathbb{P}(N(t) < n) $$
* $$ G_k|G_n = t_0 \sim U(0, t_0), \forall k \in \Set{1, 2, 3, \cdots, n - 1} $$
* $$ G_k | N(t_0) = n \sim U(0, t_0), \forall k \in \Set{1, 2, 3, \cdots, n}, \forall t_0 > 0 $$
* $$ N(b, c)|N(a, d) = n \sim B\bigg(n, p = \frac{c-b}{d - a}\bigg), \forall a, b, c, d \in \mathbb{R} : 0 \leq a \leq b \leq c \leq d $$ que es la [[Distribución Binomial]].
* $$ N(a)|G_n = b \sim B \bigg(n - 1, p = \frac{a}{b} \bigg) $$ que es la [[Distribución Binomial]].
* $$ \mathbb{P}(S_k > t_0 | N(t_1) = n) = \mathbb{P}(S_{k - n} > t_0), \forall t_0 > t_1 , \forall k > n $$