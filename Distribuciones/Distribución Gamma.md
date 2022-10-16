### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución Gamma de parámetros $\lambda$ y $\nu$ si su [[Función de densidad]] es $$ f_X(x) = \frac{\lambda^\nu}{\Gamma(\nu)} \cdot x^{\nu - 1} \cdot e^{-\lambda \cdot x} $$
Donde $\Gamma (\nu)$ es la [[Función Gamma]] evaluada en $\nu$.

##### Notación
$$ X \sim \Gamma(\nu, \lambda) $$
#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = [0, \infty)$ 
* $\nu > 0$ y $\lambda > 0$
* La [[Esperanza]] es $E[X] = \frac{\nu}{\mu}$, si $\nu \in \mathbb{N}$ entonces su [[Supervivencia]] es $S(t) = \displaystyle \sum_{n = 0}^{\nu - 1} \frac{e^{-\lambda \cdot t} \cdot (\lambda \cdot t)^n}{n!}$ y la [[Varianza]] es $Var(X) = \frac{\nu}{\lambda^2}$.

### Observaciones
---
La función $\Gamma(t)$ crece muy rápidamente, y para evitar problemas numéricos en algunos algoritmos conviene adaptar las formulas para que aparezca el logaritmo de la función $log|\Gamma(t)|$ 

Dado $X$ con distribución Gamma de parametros $1$ y $\lambda$, $X \sim \Gamma(1, \lambda)$ es equivalente a una [[Distribución exponencial]], y es equivalente a una [[Distribución Weibull]] de parametros $1$ y $\frac{1}{\lambda}$, $X \sim Wei(1, \frac{1}{\lambda})$. 

Dado $X$ con distribución Gamma de parametros $\frac{k}{2}$ y $\frac{1}{2}$, con $k \in \mathbb{N}$, $X \sim \Gamma(\frac{k}{2}, \frac{1}{2})$ es equivalente a una [[Distribución Chi cuadrado]].