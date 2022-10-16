### Definición
---
Sea $M$ una [[Variable aleatoria mezcladora]] y $X$ una [[Variable aleatoria mezcla]], de manera que conozco la [[Función de probabilidad]] de $M$ y la [[Función de densidad]] de las variables aleatorias $X|M = m, \forall m \in R_M$.

La [[Función de probabilidad]] de $M$ dado que $X = x$ será $$ p_{M|X = x}(m) = \frac{f_{X|M = m}(x) \cdot \mathbb{P}(M = m)}{\displaystyle\sum_{i \in R_M} f_{X|M = i}(x) \cdot \mathbb{P}(M = i)} $$

### Observación
---
Es el equivalente a la [[Formula de Bayes]], utilizando [[Probabilidad condicional]]. No se puede usar la definición ya que $\mathbb{P}(X = x) = 0$ ya que sabemos que $X$ es una [[Variable aleatoria continua]].