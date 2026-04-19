---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 16
---

# Solución del Ejercicio 16

Para probar la igualdad de dos conjuntos $X = Y$, debemos demostrar la doble inclusión $X \subseteq Y$ y $Y \subseteq X$. Alternativamente, podemos probar la equivalencia lógica de las condiciones de pertenencia {puddu2012conjuntos}.

Sean $A, B$ y $C$ conjuntos cualesquiera.

### i) $(A \cup B) \times C = (A \times C) \cup (B \times C)$
Sea $(x, y)$ un elemento cualquiera:
$(x, y) \in (A \cup B) \times C \iff x \in (A \cup B) \land y \in C$
$\iff (x \in A \lor x \in B) \land y \in C$
$\iff (x \in A \land y \in C) \lor (x \in B \land y \in C)$
$\iff (x, y) \in (A \times C) \lor (x, y) \in (B \times C)$
$\iff (x, y) \in (A \times C) \cup (B \times C)$

### ii) $(A \cap B) \times C = (A \times C) \cap (B \times C)$
$(x, y) \in (A \cap B) \times C \iff x \in (A \cap B) \land y \in C$
$\iff (x \in A \land x \in B) \land y \in C$
$\iff (x \in A \land y \in C) \land (x \in B \land y \in C)$
$\iff (x, y) \in (A \times C) \land (x, y) \in (B \times C)$
$\iff (x, y) \in (A \times C) \cap (B \times C)$

### iii) $(A - B) \times C = (A \times C) - (B \times C)$
$(x, y) \in (A - B) \times C \iff x \in (A - B) \land y \in C$
$\iff (x \in A \land x \notin B) \land y \in C$
$\iff (x \in A \land y \in C) \land (x \notin B \land y \in C)$
$\iff (x, y) \in (A \times C) \land \neg (x \in B \land y \in C)$
$\iff (x, y) \in (A \times C) \land (x, y) \notin (B \times C)$
$\iff (x, y) \in (A \times C) - (B \times C)$

### iv) $(A \triangle B) \times C = (A \times C) \triangle (B \times C)$
Utilizando que $X \triangle Y = (X \cup Y) - (X \cap Y)$:
$(A \triangle B) \times C = ((A \cup B) - (A \cap B)) \times C$
Por el punto (iii):
$= ((A \cup B) \times C) - ((A \cap B) \times C)$
Por los puntos (i) e (ii):
$= ((A \times C) \cup (B \times C)) - ((A \times C) \cap (B \times C))$
Por definición de diferencia simétrica:
$= (A \times C) \triangle (B \times C)$

Estas propiedades muestran que el producto cartesiano se comporta de manera distributiva respecto a las operaciones de unión, intersección, diferencia y diferencia simétrica {uba2017fasciculo9}.
$\square$
