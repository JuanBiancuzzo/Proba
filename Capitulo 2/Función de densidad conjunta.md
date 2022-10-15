### Definición
---
Sean $X$, $Y$ dos [[Variable aleatoria continua]], una función de densidad de probabilidad $f_{X, Y}(x, y)$ de estas dos variables es una función que satisface:

1) $f_{X, Y}(x, y) \geq 0$
2) $\iint_{(x, y) \in \mathbb{R}^2} f_{X, Y}(x, y) dx dy = 1$


#### Calculo de probabilidad en un intervalo
---
Dado $X$, $Y$ dos [[Variable aleatoria continua]], se caclula la probabilidad en un intervalo $A$ como
$$ \mathbb{P}((X, Y) \in A) = \iint_A f_{X, Y}(x, y) dx dy $$

### Teorema
---
Sea $F_{X,Y}(x, y)$ la [[Función de distribución para vector aleatorio]] de un [[Vector aleatorio]] de variables complejas, luego $$ f_{X,Y}(x,y) = \frac{\partial^2 F_{X,Y}(x,y)}{\partial x \cdot \partial y} $$
