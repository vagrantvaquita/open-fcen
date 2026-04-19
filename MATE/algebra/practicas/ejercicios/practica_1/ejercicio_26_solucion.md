---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 26
---

### Resolución

Sean $P=\mathcal{P}(\{1,2,...,10\})$ y la relación en $P$:
$$A\mathcal{R}B \iff (A\triangle B)\cap\{1,2,3\}=\emptyset$$

Sea $C = \{1,2,3\}$. La condición $(A\triangle B)\cap C = \emptyset$ equivale a decir que no hay elementos de $C$ que pertenezcan a $A$ pero no a $B$, ni elementos de $C$ que pertenezcan a $B$ pero no a $A$.
Esto es equivalente a:
$$A \cap C = B \cap C$$

#### i) Probar que $\mathcal{R}$ es una relación de equivalencia
Probaremos las tres propiedades fundamentales:
- **Reflexividad**: $\forall A \in P$, $A \cap C = A \cap C$ es trivialmente cierto. Luego $A\mathcal{R}A$.
- **Simetría**: Si $A\mathcal{R}B$, entonces $A \cap C = B \cap C$, lo cual implica $B \cap C = A \cap C$, es decir $B\mathcal{R}A$.
- **Transitividad**: Si $A\mathcal{R}B$ y $B\mathcal{R}D$, entonces $A \cap C = B \cap C$ y $B \cap C = D \cap C$. Por transitividad de la igualdad, $A \cap C = D \cap C$, luego $A\mathcal{R}D$.

Como cumple las tres propiedades, **$\mathcal{R}$ es una relación de equivalencia**.

**¿Es antisimétrica?**
No. Consideremos $A = \{4\}$ y $B = \{5\}$.
- $A \cap C = \emptyset$
- $B \cap C = \emptyset$
Como $A \cap C = B \cap C$, se cumple $A\mathcal{R}B$ y $B\mathcal{R}A$, pero $A \neq B$. Por lo tanto, no es antisimétrica.

#### ii) Hallar la clase de equivalencia de $A=\{1,2,3\}$
Sea $A = \{1,2,3\}$. Entonces $A \cap C = \{1,2,3\} \cap \{1,2,3\} = \{1,2,3\}$.
La clase de equivalencia de $A$ es:
$$\bar{A} = \{B \in P : B \cap C = A \cap C\} = \{B \in P : \{1,2,3\} \subseteq B\}$$
Es decir, la clase de $A$ está formada por todos los subconjuntos de $\{1,...,10\}$ que contienen obligatoriamente a los elementos $1, 2$ y $3$.

Si quisiéramos contar cuántos elementos tiene esta clase, notaríamos que los elementos $4, 5, ..., 10$ (7 elementos) pueden estar o no en $B$. Por lo tanto, hay $2^7 = 128$ conjuntos en esta clase.

---
**Cita:** {puddu2012conjuntos}
