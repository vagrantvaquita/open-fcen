---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 15
---

# Solución del Ejercicio 15

El producto cartesiano entre dos conjuntos $A$ y $B$, denotado como $A \times B$, es el conjunto de todos los pares ordenados $(a, b)$ tales que $a \in A$ y $b \in B$ {puddu2012conjuntos}.

Dados los conjuntos:
$A = \{1, 2, 3\}$
$B = \{1, 3, 5, 7\}$

### i) $A \times A$
Buscamos todos los pares $(a_1, a_2)$ con $a_1, a_2 \in A$:
$A \times A = \{ (1,1), (1,2), (1,3), (2,1), (2,2), (2,3), (3,1), (3,2), (3,3) \}$

### ii) $A \times B$
Buscamos todos los pares $(a, b)$ con $a \in A$ y $b \in B$:
$A \times B = \{ (1,1), (1,3), (1,5), (1,7), (2,1), (2,3), (2,5), (2,7), (3,1), (3,3), (3,5), (3,7) \}$

### iii) $(A \cap B) \times (A \cup B)$
Primero calculamos la intersección y la unión de $A$ y $B$:
- $A \cap B = \{ x : x \in A \land x \in B \} = \{ 1, 3 \}$
- $A \cup B = \{ x : x \in A \lor x \in B \} = \{ 1, 2, 3, 5, 7 \}$

Ahora calculamos el producto cartesiano entre estos dos nuevos conjuntos:
$(A \cap B) \times (A \cup B) = \{ 1, 3 \} \times \{ 1, 2, 3, 5, 7 \}$
$= \{ (1,1), (1,2), (1,3), (1,5), (1,7), (3,1), (3,2), (3,3), (3,5), (3,7) \}$

Notemos que el cardinal del producto cartesiano es igual al producto de los cardinales de los conjuntos: $|(A \cap B) \times (A \cup B)| = 2 \cdot 5 = 10$ {uba2017fasciculo9}.
