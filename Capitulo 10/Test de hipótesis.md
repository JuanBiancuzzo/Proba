Es una regla de decisión entre la [[Hipótesis nula]] y la [[Hipótesis alternativa]], ($H_0$ y $H_1$ respectivamente), y la expresamos como una función de la [[Muestra aleatoria]] $\delta(\underline{X})$ que puede tomar los valores $0$ y $1$.

Si $\delta(\underline{X}) = 1$ se rechaza $H_0$, y en caso contrario no se rechaza.

### Definición
---
Sea $\underline{X} = \left( X_1, \cdots, X_n  \right)$ una [[Muestra aleatoria]] de una [[Población]] con distribución $F_\theta(x)$, $\theta \in \Theta$. Sean $\Theta_1$ y $\Theta_2$ una [[Partición]] de $\Theta$. Un test para este problema es una regla de decisión basada en $\underline{X}$ para decidir entre la [[Hipótesis nula]] y la [[Hipótesis alternativa]] $$ H_0 : \theta \in \Theta_1 ~~~ \text{y} ~~~ H_1 : \theta \in \Theta_2 $$
Entonces 
$$ \mathbb{P}(\text{"Error de tipo 1"}) = \mathbb{P}_\theta(\text{"Rechazar }H_0 \text{"}), ~ \theta \in \Theta_1 $$
$$ \mathbb{P}(\text{"Error de tipo 2"}) = \mathbb{P}_\theta(\text{"Rechazar } H_1 \text{"}), ~ \theta \in \Theta_2 $$
Con los errores siendo [[Error de tipo 1]] y [[Error de tipo 2]].

Y la [[Potencia]] del test: $$ \Pi_\delta(\theta) = \mathbb{P}_\theta(\text{"Rechazar }H_0 \text{"}) = \mathbb{P}_\theta(\delta(\underline{X}) = 1) = E_\theta[\delta(\underline{X})] $$