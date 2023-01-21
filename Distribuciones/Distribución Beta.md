---
distribucion: Continua
---

### Definición
---
Se dice que una [[Variable aleatoria]] $X$ tiene distribución Beta de parametros $a$ y $b$ si su [[Función de densidad]] es $$ f_X(x) = \frac{\Gamma(a + b)}{\Gamma(a)\cdot\Gamma(b)} \cdot x^{a - 1} \cdot (1 - x)^{b - 1} $$ donde $\Gamma(x)$ es la [[Función Gamma]].

##### Notación
$$ X \sim \beta(a, b) $$
#### Notas
---
* El [[Soporte]] de $X$ es $Sop(X) = (0, 1)$ 
* $a > 0$ y $b > 0$
* La [[Esperanza]] es $E[X] = \displaystyle\frac{a}{a + b}$ y la [[Varianza]] es $Var(X) = \displaystyle\frac{a \cdot b}{(a + b)^2 \cdot (a + b + 1)}$.

### Observaciones
---
Dada $X$ con distribución Beta de parametros $1$ y $1$, $X \sim \beta(1, 1)$ es equivalente a una [[Distribución uniforme]] de parametros $0$ y $1$, $X \sim U(0, 1)$.