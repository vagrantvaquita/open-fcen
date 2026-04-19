---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 13
---

# Solución del Ejercicio 13

Para analizar estas afirmaciones, utilizaremos las definiciones elementales de las operaciones entre conjuntos: unión ($\cup$), intersección ($\cap$), diferencia ($-$), complemento ($A^c$) y diferencia simétrica ($\triangle$) {puddu2012conjuntos}.

### i) $(A \triangle B) - C = (A - C) \triangle (B - C)$
**Verdadero**.
Demostración:
Sabemos que $X - Y = X \cap Y^c$ y $X \triangle Y = (X \cap Y^c) \cup (Y \cap X^c)$.
Lado izquierdo:
$((A \cap B^c) \cup (B \cap A^c)) \cap C^c = (A \cap B^c \cap C^c) \cup (B \cap A^c \cap C^c)$.
Lado derecho:
$(A - C) \triangle (B - C) = (A \cap C^c) \triangle (B \cap C^c)$.
Por definición de $\triangle$:
$((A \cap C^c) \cap (B \cap C^c)^c) \cup ((B \cap C^c) \cap (A \cap C^c)^c)$.
Aplicando leyes de De Morgan:
$((A \cap C^c) \cap (B^c \cup C)) \cup ((B \cap C^c) \cap (A^c \cup C))$.
Distribuyendo:
$(A \cap C^c \cap B^c) \cup (A \cap C^c \cap C) \cup (B \cap C^c \cap A^c) \cup (B \cap C^c \cap C)$.
Como $C^c \cap C = \emptyset$, los términos del medio se anulan:
$(A \cap B^c \cap C^c) \cup (B \cap A^c \cap C^c)$.
Ambos lados coinciden.

### ii) $(A \cap B) \triangle C = (A \triangle C) \cap (B \triangle C)$
**Falso**.
Contraejemplo: Sean $A = \{1\}$, $B = \{2\}$, $C = \{1, 2\}$.
- $A \cap B = \emptyset \Rightarrow (A \cap B) \triangle C = \emptyset \triangle \{1, 2\} = \{1, 2\}$.
- $A \triangle C = \{2\}$ y $B \triangle C = \{1\}$.
- $(A \triangle C) \cap (B \triangle C) = \{2\} \cap \{1\} = \emptyset$.
Como $\{1, 2\} \neq \emptyset$, la igualdad no se cumple.

### iii) $C \subseteq A \Rightarrow B \cap C \subseteq (A \triangle B)^c$
**Verdadero**.
Demostración:
Recordemos que $(A \triangle B)^c = (A \cap B) \cup (A^c \cap B^c)$.
Sea $x \in B \cap C$. Entonces $x \in B$ y $x \in C$.
Como por hipótesis $C \subseteq A$, si $x \in C$ entonces $x \in A$.
Por lo tanto, $x \in A$ y $x \in B$, lo que implica que $x \in A \cap B$.
Como $A \cap B \subseteq (A \cap B) \cup (A^c \cap B^c) = (A \triangle B)^c$, concluimos que $x \in (A \triangle B)^c$.

### iv) $A \triangle B = \emptyset \iff A = B$
**Verdadero**.
Demostración:
- ($\Rightarrow$) Si $A \triangle B = (A - B) \cup (B - A) = \emptyset$, entonces necesariamente $A - B = \emptyset$ y $B - A = \emptyset$ (pues la unión de conjuntos es vacía solo si cada uno es vacío). De $A - B = \emptyset$ se sigue que $A \subseteq B$. De $B - A = \emptyset$ se sigue que $B \subseteq A$. Por lo tanto, $A = B$.
- ($\Leftarrow$) Si $A = B$, entonces $A \triangle B = (A - A) \cup (A - A) = \emptyset \cup \emptyset = \emptyset$ {uba2017fasciculo9}.
$\square$
