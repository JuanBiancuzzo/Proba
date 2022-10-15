### Definición
---
Sea $(X, Y)$ un [[Vector aleatorio]], las [[Variable aleatoria]] $X$ e $Y$ son independientes si y solo si 
$$ \mathbb{P}((X \in A) \cdot (Y \in B)) = \mathbb{P}(X \in A) \cdot \mathbb{P}(Y \in B), \forall A, B \subseteq \mathbb{R} $$

#### Propiedades
---
1) Se dice que $X_1, X_2, ... , X_n$ son [[Variable aleatoria]] independientes si la [[Función de distribución para vector aleatorio]] es igual al producto de las [[Función de distribución marginal]] para cada [[Variable aleatoria]]. $$ F_{X_1, X_2, \cdots, X_n}(x_1, x_2, \cdots, x_n) = F_{X_1}(x_1) \cdot ... \cdot F_{X_n}(x_n) = \prod_{i \in [1, n]} F_{X_i}(x_i) $$
2) Se dice que las [[Variable aleatoria discreta]] $X_1, \cdots, X_n$ son independientes si la [[Función de probabilidad para vector aleatorio]] es igual al producto de las [[Función de probabilidad marginal]] para cada [[Variable aleatoria discreta]]. $$ p_{X_1, \dots, X_n}(x_1, \cdots, x_n) = p_{x_1}(x_1) \cdot ... \cdot p_{X_n}(x_n) = \prod_{i \in [1, n]} p_{X_i}(x_i) $$
3) Se dice que las [[Variable aleatoria continua]] $X_1, \cdots, X_n$ son independientes si la [[Función de densidad conjunta]] es igual al producto de las [[Función de densidad marginal]] para cada [[Variable aleatoria continua]]. $$  f_{X_1, \dots, X_n}(x_1, \cdots, x_n) = f_{x_1}(x_1) \cdot ... \cdot f_{X_n}(x_n) = \prod_{i \in [1, n]} f_{X_i}(x_i)  $$
