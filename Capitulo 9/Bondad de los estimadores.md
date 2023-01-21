### Definición
---
Dada $X_1, \cdots, X_n \sim F_\theta(x)$, $\theta \in \Theta$ una [[Muestra aleatoria]]. [[Estimador|Estimamos]] $\theta$ por $\hat{\theta}$. El Riesgo de estimar a $\theta$ con $\hat{\theta}$ se mide con el error cuadrático medio $$ R(\theta, \hat{\theta}) = ECM(\hat{\theta}) = E\bigg[(\theta - \hat{\theta})^2\bigg] $$ donde $E[\cdot]$ es la [[Esperanza]].

Diremos que un estimador óptimo para $\theta$ será $\hat{\theta}^*$ tal que $$ ECM(\hat{\theta}^*) \le ECM(\hat{\theta}), ~\forall \hat{\theta} $$
### Propiedad
---
Dado un [[Estimador]] de $\theta$, se tiene que $$ EMC(\hat{\theta}) = Var_\theta(\hat{\theta}) + B(\hat{\theta})^2 $$ donde $Var_\theta$ es la [[Varianza]] y $B$ es el [[Sesgo]].