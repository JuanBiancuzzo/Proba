### Definición
---
Sea $\underline{X} = \left( X_1, \cdots, X_n \right)$ una [[Muestra aleatoria]] con distribución perteneciente a una [[Familia exponencial]], luego
1) si $c(\theta)$ es creciente, el [[Test de hipótesis|test]] para $H_0 : \theta \le \theta_1$ vs $H_1 : \theta > \theta_1$ será $$ \delta(\underline{X}) = \begin{cases} 
	1 & \text{si } T > k_\alpha \\
	0 & \text{si } T \le k_\alpha 
\end{cases} $$ Que para un [[Test con nivel de significación|nivel]] $\alpha$ dado se tendrá $$ \alpha = \mathbb{P}_{\theta_1}(\delta(\underline{X}) = 1) $$Recordando que $T$ esta dado por [[Teorema de la familia exponencia]].

2) si $c(\theta)$ es decreciente, el test para $H_0 : \theta \le \theta_1$ vs $H_1 : \theta > \theta_1$ será $$ \delta(\underline{X}) = \begin{cases} 
	1 & \text{si } -T > k_\alpha \\
	0 & \text{si } -T \le k_\alpha 
\end{cases} $$Que para un [[Test con nivel de significación|nivel]] $\alpha$ dado se tendrá $$ \alpha = \mathbb{P}_{\theta_1}(\delta(\underline{X}) = 1) $$
