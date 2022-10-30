### Definición
---
Dado un [[Proceso puntual]], donde los arribos sean independientes y entre dos arribos consecutivos su distancia tenga [[Distribución exponencial]]. Con la siguiente notación: $$ \Pi \sim PPP(\lambda) $$ donde $\lambda$ es la intensidad o tasa de ocurrencia


### Variables utiles
---
Por lo que vamos a definir las siguientes [[Variable aleatoria|variables aleatorias]]. 

Definimos como $N(a, b)$  a la cantidad de arribos entre $a$ y $b$, donde $a < b$. Esta variable tiene [[Distribución de Poisson]], $N(a, b) \sim Poi(\mu = \lambda \cdot (b - a))$. Por convención de notación diremos que $N(0, t) \equiv N(t)$.

Definimos a las variables $G_n$ como el tiempo hasta el $n$-esimo arribo. Donde cumplen que tienen [[Distribución Gamma]], $G_n \sim \Gamma(n, \lambda)$.

Definimos las variables $T_{i,j}$ como el tiempo entre dos arribos consecutivos, el $i$-esimo y el $j$-esimo. Entonces son $T_{i, j} = G_j - G_i \sim \varepsilon(\lambda)$ pero por convención llamaremos $T_i$ donde cumple $T_i = G_i - G_{i - 1}$ y definimos $G_0$ como $0$.

