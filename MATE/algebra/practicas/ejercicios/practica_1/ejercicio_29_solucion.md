---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Funciones
practica: 1
ejercicio: 29
---

# Ejercicio 29

Determinar si $\mathcal{R}$ es función de $A$ en $B$ en los casos:

* ii) $A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,a),(4,b),(5,c),(3,d)\}$
* iii) $A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,d),(4,b),(5,c)\}$
* iv) $A=\mathbb{N}$, $B=\mathbb{R},$ $\mathcal{R}=\{(a,b)\in\mathbb{N}\times\mathbb{R}/a=2b-3\}$
* v) $A=\mathbb{R},$ $B=\mathbb{N}$, $\mathcal{R}=\{(a,b)\in\mathbb{R}\times\mathbb{N}/a=2b-3\}$
* vi) $A=\mathbb{Z}$, $B=\mathbb{Z}$ $\mathcal{R}=\{(a,b)\in\mathbb{Z}\times\mathbb{Z}/a+b$ es divisible por 5\}

## Resolución

Recordemos que una relación $\mathcal{R} \subseteq A \times B$ es una **función** de $A$ en $B$ si cumple dos condiciones fundamentales:
1. **Existencia (Dominio):** Todo elemento del conjunto de partida $A$ tiene al menos una imagen en $B$. Es decir, $\forall x \in A, \exists y \in B : (x,y) \in \mathcal{R}$.
2. **Unicidad:** Cada elemento del conjunto de partida $A$ tiene a lo sumo una imagen en $B$. Es decir, si $(x,y) \in \mathcal{R}$ y $(x,z) \in \mathcal{R}$, entonces $y=z$.

---

### Caso ii)
$A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,a),(4,b),(5,c),(3,d)\}$

Observamos los pares que tienen como primera componente al número $3$: $(3,a)$ y $(3,d)$. 
Dado que $a \neq d$, el elemento $3$ tiene **dos imágenes distintas**. 
**Conclusión:** No es función porque no cumple la condición de unicidad.

---

### Caso iii)
$A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,d),(4,b),(5,c)\}$

Verificamos las condiciones:
1. **Existencia:** Cada elemento de $A=\{1,2,3,4,5\}$ aparece exactamente una vez como primera componente.
2. **Unicidad:** No hay ningún elemento de $A$ asociado a dos elementos distintos de $B$.
**Conclusión:** Sí es función.

---

### Caso iv)
$A=\mathbb{N}$, $B=\mathbb{R},$ $\mathcal{R}=\{(a,b)\in\mathbb{N}\times\mathbb{R}/a=2b-3\}$

Para que sea función, para cada $a \in \mathbb{N}$ debe existir un único $b \in \mathbb{R}$ tal que $a = 2b-3$.
Despejamos $b$ en función de $a$:
$$a = 2b - 3 \iff a + 3 = 2b \iff b = \frac{a+3}{2}$$
Dado que $a$ es un número natural, $a+3$ también lo es, y su mitad $\frac{a+3}{2}$ es siempre un número real (en particular, es un número racional). Además, el valor de $b$ está unívocamente determinado por $a$.
**Conclusión:** Sí es función.

---

### Caso v)
$A=\mathbb{R},$ $B=\mathbb{N}$, $\mathcal{R}=\{(a,b)\in\mathbb{R}\times\mathbb{N}/a=2b-3\}$

Nuevamente, la relación impone que $b = \frac{a+3}{2}$. Sin embargo, ahora el conjunto de llegada es $B = \mathbb{N}$.
Para que sea función, para *todo* $a \in \mathbb{R}$ debería cumplirse que $b = \frac{a+3}{2}$ sea un número natural.
Si tomamos $a=2$, tenemos $b = \frac{2+3}{2} = 2.5$. Como $2.5 \notin \mathbb{N}$, el elemento $2 \in A$ **no tiene imagen** en $B$.
**Conclusión:** No es función porque no cumple la condición de existencia.

---

### Caso vi)
$A=\mathbb{Z}$, $B=\mathbb{Z}$, $\mathcal{R}=\{(a,b)\in\mathbb{Z}\times\mathbb{Z}/a+b \text{ es divisible por } 5\}$

La condición dice que $a+b = 5k$ para algún $k \in \mathbb{Z}$. Despejando $b$: $b = 5k - a$.
Si tomamos $a=0$, los valores de $b$ que cumplen la condición son todos los múltiplos de $5$ ($b \in \{0, 5, 10, -5, \dots\}$).
Esto significa que el elemento $0 \in \mathbb{Z}$ tiene **infinitas imágenes** distintas en $B=\mathbb{Z}$.
**Conclusión:** No es función porque no cumple la condición de unicidad.

## Bibliografía
- {puddu2012conjuntos}
- {uba2017fasciculo9}
