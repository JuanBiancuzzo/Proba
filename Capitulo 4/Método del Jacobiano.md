### Definición
---
Suponga que $Y_1$ e $Y_2$ son [[Variable aleatoria continua]] con [[Función de densidad conjunta]] y que para todo $(y_1, y_2)$ tal que $f_{Y_1, Y_2}(y_1, y_2) > 0$, $u_1 = h_2(y_1, y_2)$, $u_2 = h_2(y_1, y_2)$ es una transformación $1$ a $1$ de $(y_1, y_2)$ y $(u_1, u_2)$ con inversa $y_1 = h_1^{-1}(u_1, u_2)$, $y_2 = h_2^{-1}(u_1, u_2)$.

Si las inversas tienen derivadas parciales continuas respecto de $u_1$ y $u_2$ con jacobiano $J$, entonces 
$$ f_{U_1, U_2}(u_1, u_2) = \frac{f_{Y_1, Y_2}(y_1, y_2)}{|J|}\Bigg|_{y_1 = h_1^{-1}, y_2 = h_2^{-1}} $$