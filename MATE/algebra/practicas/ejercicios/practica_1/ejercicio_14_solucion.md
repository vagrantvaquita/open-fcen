---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 14
---

# Solución del Ejercicio 14

Probar identidades entre conjuntos requiere, en general, demostrar la igualdad de las funciones características o utilizar las leyes del álgebra de conjuntos (Leyes de De Morgan, distributividad, etc.) {puddu2012conjuntos}.

### i) $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$
La intersección es distributiva respecto a la diferencia simétrica.
$A \cap (B \triangle C) = A \cap ((B \cap C^c) \cup (C \cap B^c))$
$= (A \cap B \cap C^c) \cup (A \cap C \cap B^c)$.
Por otro lado:
$(A \cap B) \triangle (A \cap C) = ((A \cap B) - (A \cap C)) \cup ((A \cap C) - (A \cap B))$
$= ((A \cap B) \cap (A^c \cup C^c)) \cup ((A \cap C) \cap (A^c \cup B^c))$
$= (A \cap B \cap A^c) \cup (A \cap B \cap C^c) \cup (A \cap C \cap A^c) \cup (A \cap C \cap B^c)$
$= \emptyset \cup (A \cap B \cap C^c) \cup \emptyset \cup (A \cap C \cap B^c)$
$= (A \cap B \cap C^c) \cup (A \cap C \cap B^c)$. Queda probado.

### ii) $A - (B - C) = (A - B) \cup (A \cap C)$
$A - (B - C) = A \cap (B \cap C^c)^c = A \cap (B^c \cup C)$
$= (A \cap B^c) \cup (A \cap C) = (A - B) \cup (A \cap C)$.

### iii) $A \triangle B \subseteq (A \triangle C) \cup (B \triangle C)$
Sea $x \in A \triangle B$. Entonces $x$ pertenece a exactamente uno de los conjuntos $A$ o $B$.
- Si $x \in A$ y $x \notin B$: Si $x \in C$, entonces $x \in C$ y $x \notin B$, luego $x \in B \triangle C$. Si $x \notin C$, entonces $x \in A$ y $x \notin C$, luego $x \in A \triangle C$.
- Si $x \in B$ y $x \notin A$: Si $x \in C$, entonces $x \in C$ y $x \notin A$, luego $x \in A \triangle C$. Si $x \notin C$, entonces $x \in B$ y $x \notin C$, luego $x \in B \triangle C$.
En cualquier caso, $x \in (A \triangle C) \cup (B \triangle C)$.

### iv) $(A \cap C) - B = (A - B) \cap C$
$(A \cap C) - B = (A \cap C) \cap B^c = (A \cap B^c) \cap C = (A - B) \cap C$. (Propiedad asociativa y conmutativa de $\cap$).

### v) $A \subseteq B \Rightarrow A \triangle B = B \cap A^c$
Si $A \subseteq B$, entonces $A - B = \emptyset$.
$A \triangle B = (A - B) \cup (B - A) = \emptyset \cup (B - A) = B \cap A^c$.

### vi) $A \subseteq B \iff B^c \subseteq A^c$
Esta es la contraposición aplicada a la pertenencia:
$x \in A \Rightarrow x \in B$ es equivalente a $x \notin B \Rightarrow x \notin A$.
Es decir, $x \in B^c \Rightarrow x \in A^c$ {uba2017fasciculo9}.

### vii) $A \cap C = \emptyset \Rightarrow A \cap (B \triangle C) = A \cap B$
Por el punto (i), $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$.
Si $A \cap C = \emptyset$, entonces:
$(A \cap B) \triangle \emptyset = ((A \cap B) - \emptyset) \cup (\emptyset - (A \cap B)) = A \cap B \cup \emptyset = A \cap B$.
$\square$
