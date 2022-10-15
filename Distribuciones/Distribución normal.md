### Definición
---
La [[Variable aleatoria]] $X$ que toma los valores $x \in \mathbb{R}$ tiene una distribucipon normal si su [[Función de densidad]] es de la forma $$ f_X(x) = \varphi(x) = \frac{1}{\sqrt{2 \cdot \pi \cdot \sigma }} \cdot e^{-(x - \mu)^2 \cdot (2 \cdot \sigma^2)^{-1}} $$
##### Notación
$$ X \sim N(\mu, \sigma^2) $$

#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = \mathbb{R}$ 
* $\mu \in \mathbb{R}, \sigma^2 > 0$
* La [[Esperanza]] es $E[X] = \mu$ y la [[Varianza]] es $Var(X) = \sigma$.



### Calculo de probabilidad
---
$$ \Phi(x) = F_X(x) = \mathbb{P}(X \leq x) = \int_{-\infty}^{\infty} \frac{1}{\sqrt{2 \cdot \pi \cdot \sigma} } \cdot e^{-(t - \mu)^2 \cdot (2 \cdot \sigma^2)^{-1}} dt $$

#### Observación
---
	Para cuando $\mu = 1$ y $\sigma = 0$ se le dice distrobución normal estandar.