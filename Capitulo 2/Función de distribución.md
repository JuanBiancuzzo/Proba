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
	\mathbb{P}(X \in I) = \mathbb{P}(a < X \leq b) = F_X(b) - (F_X(a) - \mathbb{P}(a)) & I = [a, b] \\
\end{matrix}$$
 

#### Para [[Variable aleatoria continua]]
---
Se puede calcular la probabilidad de un punto, como 
$$ F_X(x) = \mathbb{P}(X \leq x) = \int_{-\infty}^x f_X(t) dt $$
## Con [[Vector aleatorio]]
---
Sea $X = (X_1, \cdot, X_n)$ un [[Vector aleatorio]] de dimensión $n$, definimos una función de distribución de $X$ como $$ F_X(x) = \mathbb{P}(X_1 \leq x_1, \cdots, X_n \leq x_n) $$

#### Propiedades, para cuando $\mathbb{X} = (X, Y)$
1) $\lim_{X, Y \to \infty}F_\mathbb{X}(x, y) = 1$, $\lim_{X,Y \to -\infty}F_\mathbb{X}(x, y) = 0$
2) $F_\mathbb{X}(x, y)$ es monotona no decreciente en cada variable
3) $F_\mathbb{X}(x, y)$ es continua a derecha en cada variable


#### Calculo de probabilidad en un intervalo de $\mathbb{R}^2$
---
 Dado una [[Vector aleatorio]] $\mathbb{X}$, se puede caclular la probabilidad de que $\mathbb{X}$ este en un intervalo $(a_1, b_1) \times (a_2, b_2)$  
 $$\mathbb{P}((X, Y) \in (a_1, b_1) \times (a_2, b_2)) = F_\mathbb{X}(b_1, b_2) - F_\mathbb{X}(a_1, b_2) - F_\mathbb{X}(b_1, a_2) + F_\mathbb{X}(a_1, a_2)$$