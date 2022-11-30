### Definición
---
Dada una sucesión de [[Estimador|estimadores]] $\hat{\theta}_n$ de $\theta$, decimos que $T = \hat{\theta}$ es (debilmente) consistente si $$ 
\lim_{n \to \infty} \mathbb{P}(|T - \theta| > \varepsilon) = 0, ~\forall \varepsilon > 0 $$

### Teorema
---
Sea una sucesión de [[Estimador|estimadores]] $\hat{\theta}_n$ de $\theta$. Si $\lim_{n\to\infty} Var_\theta(\hat{\theta}) = 0$ y $\lim_{n\to\infty}E_\theta(\hat{\theta}) = 0$ (ver [[Varianza]] y [[Esperanza]]) entonces $\hat{\theta}_n$ es debilmente consistente.