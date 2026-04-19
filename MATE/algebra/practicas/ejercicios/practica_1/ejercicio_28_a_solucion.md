---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 28
subejercicio: a
---

# Ejercicio 28a

Sea $A=\{1,2,3,4,5,6,7,8,9,10\}$. Consideremos en $\mathcal{P}(A)$ la relación de equivalencia dada por el cardinal (es decir, la cantidad de elementos): dos subconjuntos de $A$ están relacionados si y solo si tienen la misma cantidad de elementos. ¿Cuántas clases de equivalencia distintas determina la relación? Hallar un representante para cada clase.

## Resolución

Para resolver este ejercicio, debemos recordar la definición de clase de equivalencia. Si $R$ es una relación de equivalencia sobre un conjunto $X$, la clase de equivalencia de un elemento $x \in X$ se define como:
$$[x] = \{ y \in X : (x, y) \in R \}$$

En este caso, el conjunto base es el conjunto de partes de $A$, denotado por $\mathcal{P}(A)$. La relación $\sim$ está definida como:
$$X \sim Y \iff |X| = |Y| \quad \text{para } X, Y \in \mathcal{P}(A)$$

donde $|X|$ denota el cardinal (cantidad de elementos) del conjunto $X$.

### 1. Análisis de las clases de equivalencia
Dos subconjuntos están en la misma clase si y solo si tienen el mismo cardinal. Por lo tanto, cada clase de equivalencia está determinada por un valor posible del cardinal de los subconjuntos de $A$.

Dado que $A$ tiene 10 elementos ($|A| = 10$), los posibles cardinales para un subconjunto $X \subseteq A$ son los números enteros entre $0$ (para el conjunto vacío $\emptyset$) y $10$ (para el propio conjunto $A$). Es decir:
$$|X| \in \{0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10\}$$

Cada uno de estos valores define una clase de equivalencia distinta. Por ejemplo, la clase $[ \emptyset ]$ contiene a todos los subconjuntos de cardinal 0 (solo el vacío), la clase de un conjunto con un elemento contiene a todos los subconjuntos de cardinal 1, y así sucesivamente.

### 2. Cantidad de clases
Como hay 11 cardinales posibles, la relación determina **11 clases de equivalencia distintas**.

### 3. Representantes de las clases
Un conjunto de representantes se obtiene tomando un elemento de cada clase. Una elección natural es:
- Clase cardinal 0: $\emptyset$
- Clase cardinal 1: $\{1\}$
- Clase cardinal 2: $\{1, 2\}$
- Clase cardinal 3: $\{1, 2, 3\}$
- Clase cardinal 4: $\{1, 2, 3, 4\}$
- Clase cardinal 5: $\{1, 2, 3, 4, 5\}$
- Clase cardinal 6: $\{1, 2, 3, 4, 5, 6\}$
- Clase cardinal 7: $\{1, 2, 3, 4, 5, 6, 7\}$
- Clase cardinal 8: $\{1, 2, 3, 4, 5, 6, 7, 8\}$
- Clase cardinal 9: $\{1, 2, 3, 4, 5, 6, 7, 8, 9\}$
- Clase cardinal 10: $\{1, 2, 3, 4, 5, 6, 7, 8, 9, 10\}$ (es decir, el conjunto $A$)

## Bibliografía
Esta resolución se apoya en las definiciones de relaciones de equivalencia y conjunto de partes presentadas en:
- {puddu2012conjuntos}
- {uba2017fasciculo9}
