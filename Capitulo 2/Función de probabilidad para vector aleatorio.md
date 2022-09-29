### Definición
---
Sean $X$, $Y$ dos [[Variable aleatoria discreta]] defindas en el [[Espacio muestral]] $\Omega$ de un experimento. La función de probabilidad conjunta se define para cada par de números $(x, y)$ como 
$$ p_{X, Y}(x, y) = \mathbb{P}(X = x, Y = y) $$
Donde debe cumplir:
1) $p_{X, Y}(x, y) \geq 0$
2) $\sum_x \sum_y p_{X, Y}(x, y) = 1$


#### Caclulo de probabilidad de un intervalo
---
Dado un conjunto $A \subseteq R_{X, Y}$ es el rango [[Rango de un vector aleatorio discreto]], entonces se puede calcular la probabilidad como:
$$ \mathbb{P}((X, Y) \in A) = \sum \sum{}_{(x, y) \in A}p_{X, y}(x, y) $$
