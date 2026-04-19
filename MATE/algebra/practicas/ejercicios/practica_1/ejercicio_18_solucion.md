---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 18
---

# Solución del Ejercicio 18

Definir una relación por extensión consiste en listar todos los pares ordenados $(a, b) \in A \times B$ que satisfacen una condición dada {puddu2012conjuntos}.

Dados los conjuntos $A = \{1, 2, 3\}$ y $B = \{1, 3, 5, 7\}$, evaluamos la condición para cada par posible de $A \times B$.

### i) $(a, b) \in \mathcal{R} \iff a \le b$
- Si $a = 1$: $b \in \{1, 3, 5, 7\}$ (Todos cumplen)
- Si $a = 2$: $b \in \{3, 5, 7\}$ (1 no cumple)
- Si $a = 3$: $b \in \{3, 5, 7\}$ (1 no cumple)
$\mathcal{R} = \{ (1,1), (1,3), (1,5), (1,7), (2,3), (2,5), (2,7), (3,3), (3,5), (3,7) \}$

### ii) $(a, b) \in \mathcal{R} \iff a > b$
- Si $a = 1$: ningún $b$ cumple ($1 > 1$ es falso)
- Si $a = 2$: $b = 1$ cumple ($2 > 1$)
- Si $a = 3$: $b = 1$ cumple ($3 > 1$)
$\mathcal{R} = \{ (2,1), (3,1) \}$

### iii) $(a, b) \in \mathcal{R} \iff a \cdot b$ es par
Recordemos que un producto es par si al menos uno de sus factores es par {uba2017fasciculo9}.
- $1$ y $3$ son impares. Multiplicados por cualquier elemento de $B$ (todos impares) resultarán impares.
- $2$ es par. Multiplicado por cualquier elemento de $B$ resultará par.
Por lo tanto, solo los pares donde la primera componente es $2$ pertenecen a la relación:
$\mathcal{R} = \{ (2,1), (2,3), (2,5), (2,7) \}$

### iv) $(a, b) \in \mathcal{R} \iff a + b > 6$
Evaluamos las sumas:
- $1 + 7 = 8 > 6$. Par $(1,7)$.
- $2 + 5 = 7 > 6$. Par $(2,5)$.
- $2 + 7 = 9 > 6$. Par $(2,7)$.
- $3 + 5 = 8 > 6$. Par $(3,5)$.
- $3 + 7 = 10 > 6$. Par $(3,7)$.
- $3 + 3 = 6 \ngtr 6$.
$\mathcal{R} = \{ (1,7), (2,5), (2,7), (3,5), (3,7) \}$

Notemos que el orden de los elementos en cada par es fundamental, ya que el primer elemento pertenece a $A$ y el segundo a $B$.
