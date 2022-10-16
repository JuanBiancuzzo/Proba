### Definición
---
Sean $X$ e $Y$ variables aleatorias con $Var(Y)$ finita, la [[Varianza]] de $Y | X = x$ será $$ Var(Y|X = x) = E[(Y - E[Y|X = x])^2 | X = x] $$ donde llamaremos $\mathcal{T}(x) = Var(Y | X = x)$, con $\mathcal{T} : Sop(X) \to \mathbb{R}$.

Llamaremos varianza condicional de $Y$ dado $X$ a la [[Variable aleatoria]] $$ \mathcal{T}(X) = Var(Y|X) = E[(Y - E[Y|X])^2|X] = E[Y^2|X] - (E[Y|X])^2 $$
#### Propiedades
---
* Pitágoras $$ Var(Y) = E[Var(Y|X)] + Var(E[Y|X])$$