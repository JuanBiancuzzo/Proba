### Definición
---
Se dice que $\hat{\theta}_n$ es una sucesión de [[Estimador|estimadores]] asintóticamente normales si $\sqrt{n} \cdot (\hat{\theta}_n - q(\theta))$ converge en distribución a una [[Distribución normal|normal]] con [[Esperanza]] $0$ y [[Varianza]] $\displaystyle\frac{q'(\theta)^2}{I(\theta)}$ donde $I(\theta)$ es el [[Número de información de fisher]].


### Teorema
---
Sea $\hat{\theta}_n(\underline{X})$ un [[Método de máxima verosimilitud|EMV]] de $\theta$ [[Estimador consistente|consistente]] y sea $q(\theta)$ derivable con $q'(\theta) \ne 0 ~ \forall \theta$, entonces $q(\hat{\theta}_n)$ es asintoticamente normal para estimar a $q(\theta)$.