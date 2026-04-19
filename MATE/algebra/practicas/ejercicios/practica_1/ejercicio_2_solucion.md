---
titulo: Solución Ejercicio 2 - Práctica 1
categoria: Conjuntos
practica: 1
ejercicio: 2
---

### Análisis de Pertenencia e Inclusión en el conjunto $A=\{1,2,\{3\},\{1,2\}\}$

Para determinar la veracidad de cada afirmación, primero listamos los elementos de $A$:
$$A = \{ x_1, x_2, x_3, x_4 \}$$
donde $x_1 = 1$, $x_2 = 2$, $x_3 = \{3\}$ y $x_4 = \{1, 2\}$.

Recordamos que:
- $x \in A$ si $x$ es uno de los elementos de $A$.
- $X \subseteq A$ si cada elemento de $X$ pertenece a $A$ (i.e., $\forall y \in X, y \in A$).

#### Resolución de los ítems:

* **i) $3 \in A$ (Falso):** El número $3$ no es un elemento de $A$. Notar que $\{3\} \in A$, pero $3 \neq \{3\}$.
* **ii) $\{3\} \subseteq A$ (Falso):** Para que $\{3\}$ sea subconjunto, su único elemento, el $3$, debería pertenecer a $A$. Como vimos en (i), $3 \notin A$.
* **iii) $\{3\} \in A$ (Verdadero):** Es el tercer elemento de la lista.
* **iv) $\{\{3\}\} \subseteq A$ (Verdadero):** El único elemento de este conjunto es $\{3\}$. Como $\{3\} \in A$, entonces el conjunto que lo contiene es un subconjunto.
* **v) $\{1,2\} \in A$ (Verdadero):** Es el cuarto elemento de la lista.
* **vi) $\{1,2\} \subseteq A$ (Verdadero):** Sus elementos son $1$ y $2$. Como $1 \in A$ y $2 \in A$, el conjunto $\{1,2\}$ es un subconjunto de $A$.
* **vii) $\{\{1,2\}\} \subseteq A$ (Verdadero):** Su único elemento es $\{1,2\}$, el cual pertenece a $A$ (visto en v).
* **viii) $\{\{1,2\},3\} \subseteq A$ (Falso):** Sus elementos son $\{1,2\}$ (que pertenece a $A$) y $3$. Como $3 \notin A$, la inclusión falla.
* **ix) $\emptyset \in A$ (Falso):** El conjunto vacío no figura entre los elementos de $A$.
* **x) $\emptyset \subseteq A$ (Verdadero):** Por definición, el conjunto vacío es subconjunto de cualquier conjunto.
* **xi) $A \in A$ (Falso):** El conjunto $A$ no es un elemento de sí mismo.
* **xii) $A \subseteq A$ (Verdadero):** Todo conjunto es subconjunto de sí mismo.

{puddu2012conjuntos}
