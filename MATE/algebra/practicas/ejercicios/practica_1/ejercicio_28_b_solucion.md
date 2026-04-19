---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 28
subejercicio: b
---

# Ejercicio 28b

En el conjunto de todos los subconjuntos finitos de $\mathbb{N}$, consideremos nuevamente la relación de equivalencia dada por el cardinal: dos subconjuntos finitos de $\mathbb{N}$ están relacionados si y solo si tienen la misma cantidad de elementos. ¿Cuántas clases de equivalencia distintas determina la relación? Hallar un representante para cada clase.

## Resolución

Sea $\mathcal{F}(\mathbb{N})$ el conjunto de todos los subconjuntos finitos de $\mathbb{N}$, es decir:
$$\mathcal{F}(\mathbb{N}) = \{ X \subseteq \mathbb{N} : X \text{ es finito} \}$$
La relación $\sim$ en $\mathcal{F}(\mathbb{N})$ está dada por:
$$X \sim Y \iff |X| = |Y|$$

### 1. Análisis de las clases de equivalencia
Al igual que en el caso anterior, la clase de equivalencia de un subconjunto está determinada unívocamente por su cantidad de elementos. Como estamos considerando subconjuntos *finitos*, su cardinal debe ser un número natural o cero ($|X| \in \mathbb{N}_0$).

A diferencia del conjunto $A$ del ejercicio anterior, que tenía un tamaño máximo, el conjunto $\mathbb{N}$ es infinito. Por lo tanto, para cualquier número $n \in \mathbb{N}_0$, podemos encontrar al menos un subconjunto de $\mathbb{N}$ que tenga exactamente $n$ elementos. Por ejemplo, el conjunto $\{1, 2, \dots, n\}$.

Esto significa que para cada $n \in \mathbb{N}_0$, existe una clase de equivalencia:
$$C_n = \{ X \in \mathcal{F}(\mathbb{N}) : |X| = n \}$$

### 2. Cantidad de clases
Como existe una clase de equivalencia para cada número en $\mathbb{N}_0 = \{0, 1, 2, 3, \dots\}$, la relación determina **infinitas clases de equivalencia**. El conjunto de clases de equivalencia (el conjunto cociente) está en biyección con $\mathbb{N}_0$.

### 3. Representantes de las clases
Para hallar un representante por clase, podemos elegir, para cada $n \in \mathbb{N}_0$, un subconjunto de $\mathbb{N}$ con $n$ elementos:
- Para $n=0$: $\emptyset$
- Para $n \in \mathbb{N}$: el conjunto $I_n = \{ x \in \mathbb{N} : 1 \le x \le n \}$

Así, el conjunto de representantes es $\{\emptyset\} \cup \{ \{1, 2, \dots, n\} : n \in \mathbb{N} \}$.

## Bibliografía
Esta resolución se apoya en las definiciones de relaciones de equivalencia y cardinalidad de conjuntos finitos presentadas en:
- {puddu2012conjuntos}
- {uba2017fasciculo9}
