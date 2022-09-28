### Definición 
---
Sea $X$ una [[Variable aleatoria discreta]], se llama función de probabilidad de $X$ a una función $p_X : \mathbb{R} \to [0, 1]$ tal que $p_X(x) = \mathbb{P}(X = x)$ 

Cada resultado posible $x_i$ asociamos un numero $p_X(x_i) = \mathbb{P}(X = x_i)$ que debe cumplir:
1) $p_X(x_i) \geq 0, \forall i$ 
2) $\sum_{x \in R_X} p_X(x) = 1$
Donde $R_X$ es el [[Rango de una variable aleatoria discreta]]


#### Calculo de probabilidad de un punto
---
Sea $X$ una [[Variable aleatoria discreta]] la probabilidad de un punto, con la función de la función de forma que:
$$ p_X(x_j) = \mathbb{P}(X = x_j) = F_{X^-}(x_j) - F_{X^+}(x_j) $$
Es la [[Función de distribución]] por izquierda menos la [[Función de distribución]] por derecha.


#### Calculo de probabilidad en un intervalo
--- 
Dado un conjunto $A \subseteq R_X$ donde $R_X$ es el [[Rango de una variable aleatoria discreta]], entonces se puede calcular la probabilidad como:
$$ \mathbb{P}(X \in A) = \sum_{x \in A} P_X(x) $$


### Definición para [[Vector aleatorio]]
---
Sean $X$, $Y$ dos [[Variable aleatoria discreta]] defindas en el [[Espacio muestral]] $\Omega$ de un experimento. La función de probabilidad conjunta se define para cada par de números $(x, y)$ como 
$$ p_{X, Y}(x, y) = \mathbb{P}(X = x, Y = y) $$
Donde debe cumplir:
1) $p_{X, Y}(x, y) \geq 0$
2) $\sum_x \sum_y p_{X, Y}(x, y) = 1$


#### Caclulo de probabilidad de un intervalo
---
Dado un conjunto $A \subseteq R_{X, Y}$ es el rango [[Rango de una variable aleatoria discreta#Definición para un Vector aleatorio]], entonces se puede calcular la probabilidad como:
$$ \mathbb{P}((X, Y) \in A) = \sum \sum{}_{(x, y) \in A}p_{X, y}(x, y) $$
