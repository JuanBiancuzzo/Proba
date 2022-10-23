### Definición
---
Binomial modela la cantidad de éxitos obtenidos al repetir $n$ veces de forma independiente un experimento de Bernoulli con probabilidad $p$ de éxito.

Se dice que una [[Variable aleatoria]] $X$ tiene distribución Binomial de parámetros $n$ y $p$ si su [[Función de probabilidad]] es $$ p_X(x) = \dbinom{n}{x} \cdot p^x \cdot (1 - p)^{n - x} $$
##### Notación
$$ X \sim B(n, p) $$

#### Notas
---
* El [[Rango]] de $X$ es $R_X = \{ x \in \mathbb{Z} : 0 \leq x \leq n \}$
* $p \in (0, 1), n \in \mathbb{N}$ 
* La [[Esperanza]] es $E[X] = n \cdot p$ y la [[Varianza]] es $Var(X) = n \cdot p \cdot (1 - p)$.

### Observaciones
---
Dado $X$ con distribución binomial de parametros $1$ y $p$, $X \sim B(1, p)$ es equivalente a una [[Distribución de Bernoulli]].