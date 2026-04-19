---
titulo: Solución Ejercicio 3 - Práctica 1
categoria: Conjuntos
practica: 1
ejercicio: 3
---

### Determinación de Inclusión de Conjuntos

Recordamos que $A \subseteq B$ si y solo si para todo $x$, si $x \in A$ entonces $x \in B$.

#### Resolución de los ítems:

* **i) $A=\{1,2,3\}$, $B=\{5,4,3,2,1\}$ (Verdadero):**
  Observamos los elementos de $A$: $1, 2$ y $3$. Todos ellos pertenecen a $B$. Por lo tanto, $A \subseteq B$.

* **ii) $A=\{1,2,3\}$, $B=\{1,2,\{3\},-3\}$ (Falso):**
  Para que $A \subseteq B$, todos sus elementos deben estar en $B$. Sin embargo, $3 \in A$ pero $3 \notin B$ (el elemento $\{3\}$ es un conjunto, no el número $3$).

* **iii) $A=\{x \in \mathbb{R} / 2 < |x| < 3\}$, $B=\{x \in \mathbb{R} / x^2 < 3\}$ (Falso):**
  Analicemos los intervalos:
  - $A = \{x \in \mathbb{R} : x \in (-3, -2) \cup (2, 3) \}$.
  - $B = \{x \in \mathbb{R} : |x| < \sqrt{3} \} = (-\sqrt{3}, \sqrt{3})$.
  Como $\sqrt{3} \approx 1,73$, notamos que elementos como $2,5 \in A$ no pertenecen a $B$, pues $2,5 > \sqrt{3}$. Luego, $A \not\subseteq B$.

* **iv) $A=\{\emptyset\}$, $B=\emptyset$ (Falso):**
  El conjunto $A$ tiene un elemento: el conjunto vacío (i.e., $|A|=1$). El conjunto $B$ no tiene elementos (i.e., $|B|=0$). Como existe un elemento en $A$ ($\emptyset$) que no está en $B$, la inclusión es falsa.

{puddu2012conjuntos}
