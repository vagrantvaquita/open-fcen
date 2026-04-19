---
titulo: Solución Ejercicio 4 - Práctica 1
categoria: Conjuntos
practica: 1
ejercicio: 4
---

### Operaciones con Subconjuntos

Dados los conjuntos:
- $V = \{1, \{3\}, -2, 7, 10, \{1, 2, 3\}, 3\}$
- $A = \{1, -2, 7, 3\}$
- $B = \{1, \{3\}, 10\}$
- $C = \{-2, \{1, 2, 3\}, 3\}$

#### i) $A \cap (B \triangle C)$

Primero calculamos la diferencia simétrica $B \triangle C = (B \setminus C) \cup (C \setminus B)$:
- $B \setminus C = \{1, \{3\}, 10\}$ (pues ninguno de estos está en $C$).
- $C \setminus B = \{-2, \{1, 2, 3\}, 3\}$ (pues ninguno de estos está en $B$).
- $B \triangle C = \{1, \{3\}, 10, -2, \{1, 2, 3\}, 3\}$.

Luego, intersecamos con $A$:
$$A \cap (B \triangle C) = \{1, -2, 7, 3\} \cap \{1, \{3\}, 10, -2, \{1, 2, 3\}, 3\} = \{1, -2, 3\}$$

#### ii) $(A \cap B) \triangle (A \cap C)$

Calculamos cada intersección por separado:
- $A \cap B = \{1\}$.
- $A \cap C = \{-2, 3\}$.

Luego, calculamos la diferencia simétrica:
$$(A \cap B) \triangle (A \cap C) = \{1\} \triangle \{-2, 3\} = \{1, -2, 3\}$$

Notamos que el resultado es idéntico al ítem (i), verificando la propiedad distributiva de la intersección respecto a la diferencia simétrica: $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$.

#### iii) $A^c \cap B^c \cap C^c$

Utilizamos las Leyes de De Morgan: $A^c \cap B^c \cap C^c = (A \cup B \cup C)^c$.
Primero calculamos la unión:
$$A \cup B \cup C = \{1, -2, 7, 3, \{3\}, 10, \{1, 2, 3\}\}$$
Comparamos con el referencial $V$:
$$V = \{1, \{3\}, -2, 7, 10, \{1, 2, 3\}, 3\}$$
Como todos los elementos de $V$ están en la unión, tenemos que $A \cup B \cup C = V$. Por lo tanto:
$$(A \cup B \cup C)^c = V \setminus (A \cup B \cup C) = \emptyset$$

{puddu2012conjuntos}
