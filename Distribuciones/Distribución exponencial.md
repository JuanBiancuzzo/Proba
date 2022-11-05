 ### Definición 
---
Una [[Variable aleatoria]] tiene distribución exponencial de parametro $\lambda > 0$ si su [[Función de densidad]] esta dada por $$ f_X(x) = \lambda \cdot e^{-\lambda \cdot x} \cdot \mathbb{1}\{x > 0\} $$
##### Notación
$$ X \sim \varepsilon(\lambda)$$

#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = [0, \infty)$ 
* $\lambda > 0$
* La [[Esperanza]] es $E[X] = \frac{1}{\lambda}$, la [[Supervivencia]] es $S(t) = e^{-\lambda \cdot t}$ y la [[Varianza]] es $Var(X) = \frac{1}{\lambda^2}$.


### Propiedades
---
1) Si $X \sim \varepsilon(\lambda)$ entonces $\mathbb{P}(X > t + s | X > t) = \mathbb{P}(X > s), \forall t, s \in \mathbb{R}^+$, esto se llama propiedad de falta de memoria
2) Si $X$ es una [[Variable aleatoria continua]] y $\mathbb{P}(X > t + s | X > t) = \mathbb{P}(X > s) \forall t, s \in \mathbb{R}^+$ entonces existe $\lambda > 0$ tal que $X \sim \varepsilon(\lambda)$ 
3) Siendo $X_1, X_2, \cdots, X_n$ independientes y $X_i \sim \varepsilon(\lambda_i)$ entonces podemos definir: $$U = \min_{i \in \Set{1, \cdots, n}} X_i \sim \varepsilon(\sum_{i = 1}^n \lambda_i)$$y $$ \mathbb{P}(U = x_j) = \frac{\lambda_j}{\displaystyle\sum_{i = 1}^{n} \lambda_i}, j = 1, 2, 3, \cdots,  n $$
4) Si $X_1, \cdots X_n \sim Exp(\lambda)$, [[Variables independientes|independientes]] entre si, entonces $\displaystyle \sum_{i = 1}^{n} X_i \sim \Gamma(n, \lambda)$ su suma es una [[Distribución Gamma]].