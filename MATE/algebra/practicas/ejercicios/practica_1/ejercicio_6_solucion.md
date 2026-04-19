---
titulo: Solución Ejercicio 6 - Práctica 1
categoria: Conjuntos
practica: 1
ejercicio: 6
---

### Representación en Diagramas de Venn

Dado que no es posible generar gráficos directamente, se describe la región sombreada para cada caso en un diagrama de tres conjuntos ($A, B$ y $C$).

#### i) $(A \cup B^c) \cap C$

Para sombrear esta región, podemos analizarla por partes:
- La región $A \cup B^c$ incluye todo el interior de $A$ y todo lo que está por fuera de $B$ (el complemento de $B$).
- Al intersecarla con $C$, nos quedamos únicamente con las partes de $C$ que cumplen alguna de las dos condiciones anteriores.
- **Región resultante:** Es la unión de $A \cap C$ con $C \setminus B$. En el diagrama, sombrearíamos la zona donde $C$ se solapa con $A$ y la zona de $C$ que no se solapa con $B$.

#### ii) $A \triangle (B \cup C)$

La diferencia simétrica entre $X$ e $Y$ es $(X \setminus Y) \cup (Y \setminus X)$. Aquí $X=A$ e $Y=B \cup C$:
- **$A \setminus (B \cup C)$:** Es la parte de $A$ que no toca ni a $B$ ni a $C$.
- **$(B \cup C) \setminus A$:** Es toda la región de $B$ y $C$ que queda fuera de $A$.
- **Región resultante:** Sombrear la parte "exclusiva" de $A$ (lo que no comparte con nadie) y las partes de $B$ y $C$ que no están dentro de $A$.

#### iii) $A \cup (B \triangle C)$

La unión se toma sobre $A$ y el resultado de la diferencia simétrica entre $B$ y $C$:
- **$B \triangle C$:** Es $(B \setminus C) \cup (C \setminus B)$. Son las partes de $B$ que no están en $C$ y las partes de $C$ que no están en $B$.
- **Al unir con $A$:** Simplemente añadimos todo el conjunto $A$ a la región anterior.
- **Región resultante:** Sombrear todo $A$, más la zona de $B$ que no es de $C$, más la zona de $C$ que no es de $B$.

{puddu2012conjuntos}
