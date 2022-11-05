### Definición
---
Se dice que el [[Vector aleatorio]] $X = (X_1, X_2, \cdots, X_p)$ tiene distribución normal multivariada de dimensión $p$, de parámetros $\mu \in \mathbb{R}^p$ y $\Sigma \in \mathbb{R}^{p \times p}$ (simétrica y definida positiva), si su [[Función de densidad conjunta]] esta dada por $$ f_X(x) = \frac{1}{(2 \pi)^\frac{1}{2} \cdot (Det(\Sigma))^2} \cdot exp\bigg( -\frac{1}{2} \cdot (x - \mu)^T \cdot \Sigma^{-1} \cdot (x - \mu) \bigg) $$ donde $X$ y $x$ son vectores en $\mathbb{R}^p$.

##### Notación
$$ X \sim N_p(\mu, \Sigma) $$

#### Notas
---
Se define $\mu = (E[X_1], E[X_2], \cdots, E[X_p])$ y $\Sigma = \begin{bmatrix} Cov(X_1, X_1) && Cov(X_1, X_2) && \cdots && Cov(X_1, X_p) \\ Cov(X_2, X_1) && Cov(X_2, X_2) && \cdots && Cov(X_2, X_p) \\ \vdots && \vdots && \ddots && \vdots \\ Cov(X_p, X_1) && Cov(X_p, X_2) && \cdots && Cov(X_p, X_p)\end{bmatrix}$ .


### Propiedades
---
* Si $X \sim N_p(0, diag(\lambda_1, \cdots, \lambda_p))$ entonces $X_1, \cdots, X_p$ son [[Variables independientes|independientes]] y $X_i \sim N(0, \lambda_i)$.
* Si $X \sim N_p(\mu, \Sigma)$ y $A \in \mathbb{R}^{p \times p}$ entonces $A \cdot X + b \sim N_p(\mu = A \cdot \mu + b, \Sigma = A \cdot \Sigma \cdot A^T)$.
* Sea $Y = \displaystyle\sum_{i = 1}^{n} a_i \cdot X_i$ entonces $Y \sim N\bigg(\mu = \displaystyle\sum_{i = 1}^{n} a_i \cdot \mu_i, \sigma^2 = \sum_{i = 1}^{n} a_i^2 \cdot \sigma_i^2 \bigg)$ tiene una [[Distribución normal]].