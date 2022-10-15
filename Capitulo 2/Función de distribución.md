### Definición
---
Sea $(\Omega, \mathbb{A}, \mathbb{P})$ un [[Espacio de probabilidad]] y $X$ una [[Variable aleatoria]], definimos su función de distribución $F_X : \mathbb{R} \to [0, 1]$ dada por 
$$ F_X(x) = P(X \leq x), \forall x \in \mathbb{R} $$


### Propiedades
1) $F_X(x) \in [0, 1], \forall x \in \mathbb{R}$
2) $F_X(x)$ es monotona no decreciente
3) $F_X(x)$ es continua por derecha
4) $\lim_{x \to -\infty} F_X(x) = 0$ y $\lim_{x \to \infty} F_X(x) = 1$


#### Calculo de probabilidad en un intervalo
---
Dado una [[Variable aleatoria]] $X$, se puede calcular la probabilidad de que $X$ este en el intervalo $I$

$$ \begin{matrix}
	\mathbb{P}(X \in I) = \mathbb{P}(a < X \leq b) = F_X(b) - F_X(a) & I = (a, b] \\ \\
	\mathbb{P}(X \in I) = \mathbb{P}(a < X < b) = (F_X(b) - \mathbb{P}(b)) - F_X(a) & I = (a, b) \\ \\
	\mathbb{P}(X \in I) = \mathbb{P}(a \leq X < b) = F_X(b) - \mathbb{P}(b) - (F_X(a) - \mathbb{P}(a)) & I = [a, b) \\ \\
	\mathbb{P}(X \in I) = \mathbb{P}(a \leq X \leq b) = F_X(b) - (F_X(a) - \mathbb{P}(a)) & I = [a, b] \\
\end{matrix}$$
 

#### Para [[Variable aleatoria continua]]
---
Se puede calcular la probabilidad de un punto, como 
$$ F_X(x) = \mathbb{P}(X \leq x) = \int_{-\infty}^x f_X(t) dt $$