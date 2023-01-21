---
distribucion: Continua
---

### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución t-Studen de parametro $\nu$ si su [[Función de densidad]] es $$ f_X(t) = \frac{\Gamma(\frac{\nu + 1}{2})}{\sqrt{\nu \cdot \pi} \cdot \Gamma(\frac{\nu}{2})} \cdot \bigg(1 + \frac{t^2}{\nu} \bigg)^{-\frac{\nu + 1}{2}} $$ donde $\Gamma(x)$ es la [[Función Gamma]].

##### Notación
$$ X \sim t_\nu $$
#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = \mathbb{R}$ 
* $\nu > 0$
* La [[Esperanza]] es $E[X] = 0$ y la [[Varianza]] es $Var(X) = \frac{\nu}{\nu - 2}, \nu > 2$.

### Propiedades
---
Sean $Z \sim N(0, 1)$ ([[Distribución normal]]) y $U \sim \chi_n^2$ ([[Distribución Chi cuadrado]]), entonces si $Z$ y $U$ son [[Variables independientes|independientes]] $$ T = \frac{Z}{\sqrt{\displaystyle\frac{U}{n}}} \sim t_n $$ donde $\lim_{n \to \infty} t_n \sim N(0, 1)$.

Sean $X_1, \cdots, X_n$ son [[Variables independientes|independientes]] con $X_i \sim N(\mu, \sigma^2)$, si definimos $$S^2 = \sum_{i = 1}^n \frac{1}{n - 1} (X_i - \overline{X})^2  $$ entonces $T = \sqrt{n} \frac{(\overline{X} - \mu)}{S} \sim t_{n-1}$.