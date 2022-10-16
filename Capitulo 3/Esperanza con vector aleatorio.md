#### Casos especificos
---
Dado una [[Función de variable aleatoria#Para Vector aleatorio]] $h(X, Y)$ cualquiera

##### Con variable discreta
Sean $X$, $Y$ [[Variable aleatoria discreta]], con [[Función de probabilidad]] $p_{X, Y}(x, y)$ el valor medio de $X$, $Y$ es $$ E[h(X, Y)] = \sum_x \sum_y h(x, y) \cdot p_{X, Y}(x, y) = \sum_{(x, y) \in R_{X, Y}} h(x, y) \cdot p_{X, Y}(x, y) $$ donde $x$ e $y$ estan en [[Rango de un vector]].

##### Con varaibel continua
Sean $X$, $Y$ [[Variable aleatoria continua]], con [[Función de densidad]] $f_{X, Y}(x, y)$ el valor medio de $X$, $Y$ es $$ E[h(X, Y)] = \int_{-\infty}^{\infty} \int_{-\infty}^{\infty} h(x, y) \cdot f_{X, Y}(x, y) \cdot dx \cdot dy = \int_{(x, y) \in S_{X, Y}} h(x, y) \cdot f_{X, Y}(x, y) \cdot dx \cdot dy $$ donde $S_{X, Y}$ es el [[Soporte]] de las variables $X$ e $Y$.


### Propiedades
---
* $E\bigg[\displaystyle\sum_{i = 1}^n a_i \cdot X_i \bigg] = \displaystyle\sum_{i = 1}^n a_i \cdot E[X_i]$ 
* Si $X_1, \cdots, X_n$ son [[Variables independientes]], entonces $E\bigg[\displaystyle\prod_{i = 1}^n X_i \bigg] = \displaystyle\prod_{i = 1}^n E[X_i]$ 

### Propiedades de Orden 
Sea $X = (X_1, X_2, \cdots, X_n)$ un [[Vector aleatorio]], $g : \mathbb{R}^n \to \mathbb{R}$ una [[Función de variable aleatoria#Para Vector aleatorio]], tenemos que:
1) si $X > 0$ entonces $E[X] > 0$
2) si $g(x) > 0$ entonces $E[g(X)] > 0$
3) sea $h(x) > g(x)$ entonces $E[h(X)] > E[g(X)]$
4) $E[|X|] \geq E[X]$ 
5) $E[|X \cdot Y|] \leq \sqrt{E[X^2] \cdot E[Y^2]}$ 