### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución Weibull de parámetros $c$ y $\alpha$ si su [[Función de densidad]] es $$ f_X(x) = \frac{c}{\alpha} \bigg( \frac{x}{\alpha} \bigg)^{c-1} e^{-\bigg({\displaystyle\frac{x}{\alpha}} \bigg)^c} $$
##### Notación
$$ X \sim Wei(c, \alpha) $$

#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = [0, \infty)$ 
* $c > 0$ y $\alpha > 0$
* La [[Esperanza]] es $E[X] = \alpha \cdot \Gamma(1 + \frac{1}{c})$, la [[Supervivencia]] es $S(t) = e^{-(\frac{t}{\alpha})^2}$ y la [[Varianza]] es $Var(X) = \alpha^2 \cdot (\Gamma(1 + \frac{2}{c}) - \Gamma^2(1 + \frac{1}{c}))$ donde $\Gamma(x)$ es la [[Función Gamma]].


### Observaciones
---
Cuando se tiene una [[Variable aleatoria]] $X \sim Wei(c, 2)$ entonces $X^2 \sim Exp(\frac{1}{c^2})$ ([[Distribución exponencial]]).

Dado $X$ con distribución Gamma de parametros $1$ y $\frac{1}{\lambda}$, $X \sim Wei(1, \frac{1}{\lambda})$ es equivalente a una [[Distribución exponencial]], y es equivalente a una [[Distribución Gamma]] de parametros $1$ y $\lambda$, $X \sim \Gamma(1, \lambda)$. 