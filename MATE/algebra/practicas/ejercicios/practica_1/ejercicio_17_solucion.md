---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 17
---

# Solución del Ejercicio 17

Una relación $\mathcal{R}$ de un conjunto $A$ en un conjunto $B$ es, por definición, un subconjunto del producto cartesiano $A \times B$. Es decir, $\mathcal{R} \subseteq A \times B$ {puddu2012conjuntos}.

Dados los conjuntos $A = \{1, 2, 3\}$ y $B = \{1, 3, 5, 7\}$, analicemos cada caso:

### i) $\mathcal{R} = \{ (1,1), (1,3), (1,7), (3,1), (3,5) \}$
Verificamos cada par $(a, b)$:
- $(1,1): 1 \in A, 1 \in B$ (Ok)
- $(1,3): 1 \in A, 3 \in B$ (Ok)
- $(1,7): 1 \in A, 7 \in B$ (Ok)
- $(3,1): 3 \in A, 1 \in B$ (Ok)
- $(3,5): 3 \in A, 5 \in B$ (Ok)
Todos los pares pertenecen a $A \times B$. **Es una relación de $A$ en $B$.**

### ii) $\mathcal{R} = \{ (1,1), (1,3), (2,7), (3,2), (3,5) \}$
Verificamos el par $(3,2)$:
- $3 \in A$, pero $2 \notin B = \{ 1, 3, 5, 7 \}$.
Por lo tanto, $(3,2) \notin A \times B$. **No es una relación de $A$ en $B$** {uba2017fasciculo9}.

### iii) $\mathcal{R} = \{ (1,1), (2,7), (3,7) \}$
Verificamos cada par:
- $(1,1): 1 \in A, 1 \in B$ (Ok)
- $(2,7): 2 \in A, 7 \in B$ (Ok)
- $(3,7): 3 \in A, 7 \in B$ (Ok)
**Es una relación de $A$ en $B$.**

### iv) $\mathcal{R} = \{ (1,3), (2,1), (3,7) \}$
Verificamos cada par:
- $(1,3): 1 \in A, 3 \in B$ (Ok)
- $(2,1): 2 \in A, 1 \in B$ (Ok)
- $(3,7): 3 \in A, 7 \in B$ (Ok)
**Es una relación de $A$ en $B$.**

Una relación puede ser vacía, o ser todo el producto cartesiano. Lo fundamental es que cada primer componente pertenezca al dominio ($A$) y cada segundo componente al codominio ($B$).
