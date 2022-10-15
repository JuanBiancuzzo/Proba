### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución Gamma de parámetros $\lambda$ y $\nu$ si su [[Función de densidad]] es $$ f_X(x) = \frac{\lambda^\nu}{\Gamma(\nu)} \cdot x^{\nu - 1} \cdot e^{-\lambda \cdot x} \cdot \mathbb{1}\{x > 0\} $$
Donde se define $\Gamma (t)$ como $$ \Gamma(t) = \int_0^\infty x^{t - 1} \cdot e^{-1} \cdot dt $$
##### Notación
$$ X \sim \Gamma(\nu, \lambda) $$
#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = [0, \infty)$ 
* $\nu > 0$ y $\lambda > 0$
* La [[Esperanza]] es $E[X] = \frac{\nu}{\mu}$ y la [[Varianza]] es $Var(X) = \frac{\nu}{\lambda^2}$

### Observaciones
---
La función $\Gamma(t)$ crece muy rápidamente, y para evitar problemas numéricos en algunos algoritmos conviene adaptar las formulas para que aparezca el logaritmo de la función $log|\Gamma(t)|$ 

Cuando se tiene una [[Variable aleatoria]] $X \sim \Gamma(1, \lambda)$ es  equivalente a tener una [[Distribución exponencial]] 

### Propiedades
---
* $\Gamma(n) = (n - 1)!, \forall n \in \mathbb{N}$
* $\Gamma(t + 1) = t \cdot \Gamma(t)$
* $\Gamma(\frac{1}{2}) = \sqrt(n)$

