---
distribucion: Continua
---

### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución Chi cuadrado de parámetro $k$ si su [[Función de densidad]] es $$ f_X(x) = \frac{1}{2^{\frac{k}{2}} \cdot \Gamma(\frac{k}{2})} \cdot x^{\frac{k}{2} - 1} \cdot e^{-\frac{x}{2}} $$ donde $\Gamma(x)$ es la [[Función Gamma]].

##### Notación
$$ X \sim \chi_k^2 $$

#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = [0, \infty)$
* $k \in \mathbb{N}$
* La [[Esperanza]] es $E[X] = k$ y la [[Varianza]] es $Var(X) = 2k$.

### Propiedades
---
![[Distribución Gamma#Equivalencia con Chi cuadrado]]

Si $X_1, \cdots, X_n$ son [[Variables independientes|independientes]] con $X_i \sim \chi_{v_i}^2$, $i =1, \cdots, n$, entonces $Y = \sum_{i = 1}^n X_i$ tendrá distribución $\chi_v^2$, con $v = \sum_{i = 1}^n v_i$

Si $X_1, \cdots, X_n$ son [[Variables independientes|independientes]] con $X_i \sim N(0,1)$ ([[Distribución normal]]), y $U = \sum_{i = 1}^n X_i^2$ entonces $U \sim \chi_n^2$

Sean $X_1, \cdots, X_n$ son [[Variables independientes|independientes]] con $X_i \sim N(\mu, \sigma^2)$, entonces $W = \sum_{i = 1}^n \frac{(X_i - \overline{X})}{\sigma^2} \sim \chi_{n  - 1}^2$