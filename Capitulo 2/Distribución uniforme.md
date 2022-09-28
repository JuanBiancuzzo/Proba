### Definición
---
Para una [[Variable aleatoria continua]] se define su [[Función de densidad]] de forma que $$ f_X(x) = \frac{1}{b - a} \cdot \mathbb{1} \{ a < x < b \}$$

##### Notación
$$ X \sim U(a, b) $$


### Razonamiento
---
Supongamos que $X$ es una [[Variable aleatoria continua]]que toma todos los valores sobre el intervalo $[a, b]$. Si la [[Función de densidad]] esta dada por $$ f_X(x) = \begin{cases} 
	k & \text{ si } a < x < b \\
	0 & \text{ en otro caso }
\end{cases} $$
![[Distribución uniforme imagen.png]]

Por definición sabemos que $$ \int_{-\infty}^{\infty}f_X(x)dx = 1$$
Por lo que en nuesto caso, eso da que $$ (a - b) \cdot k = 1 $$ 
Entonces podemos encontrar el valor de $k$ como $$ k = \frac{1}{a - b} $$
