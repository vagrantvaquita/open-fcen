---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Funciones
practica: 1
ejercicio: 31
subejercicio: a
---

# Ejercicio 31a

Dadas las funciones
$$f: \mathbb{N} \to \mathbb{N}, f(n) = \begin{cases} n/6 & \text{si } n \text{ es divisible por 6} \\ 3n+1 & \text{en los otros casos} \end{cases}$$
$$g: \mathbb{N} \times \mathbb{N} \to \mathbb{N}, g(n, m) = n(m+1)$$

Calcular, de ser posible, $(f \circ g)(3, 4)$, $(f \circ g)(2, 5)$ y $(f \circ g)(3, 2)$.

## Resolución

Para calcular la composición $(f \circ g)(n, m)$, debemos aplicar primero la función $g$ a los elementos $(n, m)$ y luego aplicar la función $f$ al resultado obtenido. Es decir:
$$(f \circ g)(n, m) = f(g(n, m))$$

Recordemos las reglas de $f$:
- Si $n$ es divisible por $6$, dividimos por $6$.
- Si $n$ NO es divisible por $6$, multiplicamos por $3$ y sumamos $1$.

---

### 1. Cálculo de $(f \circ g)(3, 4)$
Primero calculamos $g(3, 4)$:
$$g(3, 4) = 3 \cdot (4+1) = 3 \cdot 5 = 15$$
Ahora aplicamos $f$ a $15$. ¿Es $15$ divisible por $6$? No ($15 = 6 \cdot 2 + 3$).
Entonces aplicamos la segunda rama de $f$:
$$f(15) = 3 \cdot 15 + 1 = 45 + 1 = 46$$
**Resultado:** $(f \circ g)(3, 4) = 46$.

---

### 2. Cálculo de $(f \circ g)(2, 5)$
Primero calculamos $g(2, 5)$:
$$g(2, 5) = 2 \cdot (5+1) = 2 \cdot 6 = 12$$
Ahora aplicamos $f$ a $12$. ¿Es $12$ divisible por $6$? Sí ($12 = 6 \cdot 2$).
Entonces aplicamos la primera rama de $f$:
$$f(12) = 12 / 6 = 2$$
**Resultado:** $(f \circ g)(2, 5) = 2$.

---

### 3. Cálculo de $(f \circ g)(3, 2)$
Primero calculamos $g(3, 2)$:
$$g(3, 2) = 3 \cdot (2+1) = 3 \cdot 3 = 9$$
Ahora aplicamos $f$ a $9$. ¿Es $9$ divisible por $6$? No ($9 = 6 \cdot 1 + 3$).
Entonces aplicamos la segunda rama de $f$:
$$f(9) = 3 \cdot 9 + 1 = 27 + 1 = 28$$
**Resultado:** $(f \circ g)(3, 2) = 28$.

## Bibliografía
- {puddu2012conjuntos}
- {uba2017fasciculo9}
