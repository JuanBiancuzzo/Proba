### Definición
---
Pascal modela la cantidad de ensayos necesarios hasta obtener $k$ éxitos si se repite de forma independiente un experimento de Bernoulli con probabilidad $p$ de éxito.

Se dice que una [[Variable aleatoria]] $X$ tiene distribución de Pascal de parámetros $k$ y $p$ si su [[Función de probabilidad]] es $$ p_X(x) = \dbinom{x -1}{k - 1} \cdot (1 - p)^{x - k} \cdot p^k$$
##### Notación
$$ X \sim Pas(k, p) $$

#### Notas
---
* El [[Rango de una variable discreta]] de $X$ es $R_X = \{x \in \mathbb{Z} : x \geq k\}$
* $p \in (0, 1)$ y $k \in \mathbb{N}$ 
* La [[Esperanza]] es $E[X] = \frac{k}{p}$ y la [[Varianza]] es $Var(X) = \frac{k \cdot (1 - p)}{p^2}$.

### Observaciones
---
Dado $X$ con Distribución de Pascal de parametros $1$ y $p$, $X \sim Pas(1, p)$ es equivalente a una [[Distribución Geométrica]]. 