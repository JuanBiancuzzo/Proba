Es el promedio ponderado que puede tomar una [[Variable aleatoria]] $X$. Analogo al centro de masa de un objeto.

### Definición
---
Sea $X$ una [[Variable aleatoria]] con [[Función de distribución]] $F_X(x) = \mathbb{P}(X \leq x)$, si $h(X)$ es una [[Función de variable aleatoria]] cualquiera de $X$, si definimos $A$ como el conjunto de [[Átomos]], entonces:
$$ E[h(X)] = \sum_{x \in A} h(x) \cdot \mathbb{P}(X = x) + \int_{x \in \mathbb{R} - A} h(x) \cdot F_{X}'(x) \cdot dx $$
##### Notación
Se puede espresar $\mu(X) = E[X]$



### Casos especificos
---
Dado una [[Función de variable aleatoria]] $h(X)$ cualquiera

#### Para variable discreta
Sea $X$ una [[Variable aleatoria discreta]] con [[Función de probabilidad]] $p_X(x)$, el valor esperado (o media) de $X$ es $$ E[h(X)] = \sum_{x \in R_X} h(x) \cdot p_X(x) $$ donde $R_X$ es el [[Rango de una variable discreta]]

#### Para variable continua
Sea $X$ una [[Variable aleatoria continua]] con [[Función de densidad]] $f_X(x)$, el valor esperado de $X$ es $$ 
E[h(X)] = \int_{x \in \mathbb{R}} h(x) \cdot f_X(x) \cdot dx $$
### Esperanza total
---
Dado los conjuntos $A_1, A_2, \cdots, A_n$ tal que $\displaystyle\bigcup_{i = 1}^{n} A_i = \mathbb{R}$ y  $\displaystyle\bigcap_{i = 1}^{n} A_i = \emptyset$, es decir la [[Partición]] del espacio $\mathbb{R}$, entonces se puede calcular la esperanza usando la [[Esperanza parcial]]: $$ E[X] = \sum_{i = 1}^{n} E[X | X \in A_i] \mathbb{P}(X \in A_i) $$ 


### Propiedad
---
* Sea $X$ una [[Variable aleatoria]], con $E[X] = \mu$ si $h(X) = a \cdot X + b$ entonces $E[h(X)] = a \cdot \mu + b$ 
* Se puede calcular la esperanza como $$ E[X] = \int_0^\infty (1 - F_X(x)) \cdot dx - \int_{-\infty}^0 F_X(x) \cdot dx $$

### Observación
---
* $E(X)$ no ne necesariamente tiene que pertenecer a $R_X$.