---
titulo: Solución Álgebra I - Práctica 1 - Ejercicio 1
---

Para resolver este ejercicio, es fundamental distinguir entre la relación de **pertenencia** ($\in$) y la de **inclusión** ($\subseteq$).

*   **Pertenencia ($x \in A$):** Se usa para indicar que un objeto $x$ es un *elemento* del conjunto $A$.
*   **Inclusión ($S \subseteq A$):** Se usa para indicar que un conjunto $S$ es un *subconjunto* de $A$, es decir, que todo elemento de $S$ es también un elemento de $A$.

Dado $A = \{1, 2, 3\}$, analicemos cada ítem:

### i) $1 \in A$
**Verdadero.** El número $1$ es uno de los objetos que listamos dentro de las llaves que definen al conjunto $A$.

### ii) $\{1\} \subseteq A$
**Verdadero.** Por definición de inclusión, $\{1\} \subseteq A$ si cada elemento de $\{1\}$ pertenece a $A$. En este caso, el único elemento es $1$, y ya vimos en (i) que $1 \in A$.

### iii) $\{2, 1\} \subseteq A$
**Verdadero.** Los elementos del conjunto $\{2, 1\}$ son $2$ y $1$. Como ambos pertenecen a $A$ ($2 \in A$ y $1 \in A$), se cumple la definición de subconjunto.

### iv) $\{1, 3\} \in A$
**Falso.** Para que esta afirmación fuera verdadera, el conjunto $\{1, 3\}$ (visto como un objeto en sí mismo) debería ser un *elemento* de $A$. Sin embargo, los elementos de $A$ son los números $1, 2$ y $3$, ninguno de los cuales es el conjunto $\{1, 3\}$.

### v) $\{2\} \in A$
**Falso.** Similar al caso anterior, $\{2\}$ es un conjunto que contiene al número $2$, pero no es un elemento de $A$. Lo que es verdadero es que $2 \in A$ y que $\{2\} \subseteq A$.

---
**Referencias:**
* {puddu2012conjuntos} Puddu, S. (2012). *Conjuntos, relaciones y funciones*.
* {uba2017fasciculo9} Departamento de Matemática, FCEyN, UBA. (2017). *Cursos de grado: Álgebra I (Fascículo 9)*.
