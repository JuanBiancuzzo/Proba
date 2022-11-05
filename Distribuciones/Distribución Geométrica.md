### Definición
---
Geométrica modela la cantidad de ensayos necesarios hasta obtener el primer éxito si se repite de forma independiente un experimento de Bernoulli con probabilidad $p$ de éxito.

Se dice que una [[Variable aleatoria]] $X$ tiene distribución Geométrica de parámetro $p$ si su [[Función de probabilidad]] es $$ p_X(x) = p \cdot (1 - p)^{x - 1} $$
##### Notación
$$ X \sim G(p) $$

#### Notas
---
* El [[Rango]] de $X$ es $R_X = \mathbb{N}$
* $p \in (0, 1)$ 
* La [[Esperanza]] es $E[X] = \frac{1}{p}$ y la [[Varianza]] es $Var(X) = \frac{(1 - p)}{p^2}$

### Propiedades
---
Si $X_1, \cdots X_n \sim G(p)$, [[Variables independientes|independientes]] entre si, entonces $\displaystyle \sum_{i = 1}^{n} X_i \sim Pas(n, p)$ su suma es una [[Distribución de Pascal]].