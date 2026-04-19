---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Conjuntos
practica: 1
ejercicio: 8
---

# Solución del Ejercicio 8

El conjunto de partes de un conjunto $A$, denotado por $\mathcal{P}(A)$, es el conjunto cuyos elementos son todos los subconjuntos de $A$. Formalmente:
$$\mathcal{P}(A) = \{S : S \subseteq A\}$$
Es importante recordar que, para cualquier conjunto $A$, se cumple que $\emptyset \in \mathcal{P}(A)$ y $A \in \mathcal{P}(A)$ {puddu2012conjuntos}. Además, si $A$ es un conjunto finito con $n$ elementos, entonces $\mathcal{P}(A)$ tiene $2^n$ elementos {uba2017fasciculo9}.

### i) $A = \{1\}$
El conjunto $A$ tiene $n=1$ elemento, por lo que $\mathcal{P}(A)$ tendrá $2^1 = 2$ elementos.
Los subconjuntos de $A$ son el conjunto vacío y el propio $A$:
$$\mathcal{P}(A) = \{ \emptyset, \{1\} \}$$

### ii) $A = \{a, b\}$
El conjunto $A$ tiene $n=2$ elementos, por lo que $\mathcal{P}(A)$ tendrá $2^2 = 4$ elementos.
Listamos los subconjuntos según su cardinalidad:
- Cardinal 0: $\emptyset$
- Cardinal 1: $\{a\}, \{b\}$
- Cardinal 2: $\{a, b\}$
$$\mathcal{P}(A) = \{ \emptyset, \{a\}, \{b\}, \{a, b\} \}$$

### iii) $A = \{1, \{1, 2\}, 3\}$
El conjunto $A$ tiene $n=3$ elementos. Notar que el objeto $\{1, 2\}$ es un **elemento** de $A$. Por lo tanto, $\mathcal{P}(A)$ tendrá $2^3 = 8$ elementos.
- Cardinal 0: $\emptyset$
- Cardinal 1: $\{1\}, \{\{1, 2\}\}, \{3\}$
- Cardinal 2: $\{1, \{1, 2\}\}, \{1, 3\}, \{\{1, 2\}, 3\}$
- Cardinal 3: $\{1, \{1, 2\}, 3\}$
$$\mathcal{P}(A) = \{ \emptyset, \{1\}, \{\{1, 2\}\}, \{3\}, \{1, \{1, 2\}\}, \{1, 3\}, \{\{1, 2\}, 3\}, \{1, \{1, 2\}, 3\} \}$$

Note que en el caso (iii), $\{\{1, 2\}\}$ es el subconjunto que contiene al elemento $\{1, 2\}$, mientras que $\{1, 2\} \subseteq A$ es una afirmación falsa ya que $2 \notin A$.
