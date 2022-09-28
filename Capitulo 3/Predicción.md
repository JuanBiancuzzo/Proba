### Definición
---
Sea $Y$ una [[Variable aleatoria]], $\mathbb{X} = (X_1, X_2, \cdots, X_n)$ un [[Vector aleatorio]], existirá alguna [[Función de variable aleatoria#Para Vector aleatorio]] $g(\mathbb{X})$ que nos sirva para predecir a $Y$. La mejor predicción es la que minimice el error cuadratico medio (que esta dado en función de la [[Esperanza]]) $$ E.C.M = E\bigg[ (Y - g(\mathbb{X}))^2 \bigg] $$

##### Notación
$g(\mathbb{X}) = \hat{Y}$

### Observación
---
* Si $g(\mathbb{X}) = c$ entonces podemos llegar a ver como $c = E[Y]$ por lo que  $E. C. M = Var(X)$ la "distancia minima" es la [[Varianza]].
* Si $g(\mathbb{X}) = a + b \cdot X$ entonces buscando el minimo de $E.C.M$ encontramos que esta en función de la [[Covarianza]] de la forma $$ \begin{cases} a = E[Y] - b \cdot E[X] \\ b = \displaystyle\frac{Cov(X, Y)}{Var(X)}  \end{cases} $$ entonces $g(\mathbb{X}) = \displaystyle\frac{Cov(X, Y)}{Var(X)} \cdot (X - E[X]) + E[Y]$, y esta es la [[Recta de regresión]].

### Nota
---
Se plantea una función $g(\mathbb{X})$ y se intenta encontrar el minimo del $E.C.M$ derivando parcialmente con todas las incognitas e igualandolas a $0$.