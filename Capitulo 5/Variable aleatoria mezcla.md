### Definición
---
Dado una [[Variable aleatoria]] $X$ se dice que es una variable aleatoria mezcla, si para una [[Partición]] $A_1, \cdots, A_n$ del [[Espacio muestral]] $\Omega$, su [[Función de distribución]] es $$ F_X(x) = \mathbb{P}(X \leq x) = \sum_{k = 1}^n F_{X|A_k}(x) \cdot \mathbb{P}(A_k) $$ donde $F_{X|A_k}(x)$ es la función de distribución de una [[Variable aleatoria condicional]].

Teniendo una [[Variable aleatoria mezcladora]] $M$, se define su [[Función de distribución]] es $$ F_X(x) = \sum_{m \in R_M} F_{X | M = m}(x) \cdot \mathbb{P}(M = m) $$ donde $R_M$ es el [[Rango]] de $M$

El calculo de la [[Esperanza]] esta dado por $$ E[X] = \sum_{m \in R_M} E[X|M=m] \cdot \mathbb{P}(M = m) $$

### Casos especificos
---

##### Con $X$ una [[Variable aleatoria discreta]]
* Entonces la [[Función de probabilidad]] se puede calcular como $$ p_X(x) = \sum_{m \in R_M} p_{X | M = m}(x) \cdot \mathbb{P}(M = m) $$ donde se usa una [[Variable discreta condicional]].

##### Con $X$ una [[Variable aleatoria continua]]
* Entonces la [[Función de densidad]] se puede calcular como $$ f_X(x) = \sum_{m \in R_M} f_{X | M = m}(x) \cdot \mathbb{P}(M = m) $$ donde se usa una [[Variable continua condicional]].
