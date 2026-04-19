---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Conjuntos
practica: 1
ejercicio: 9
---

# Solución del Ejercicio 9

Dada la equivalencia $P \iff Q$, debemos demostrar las dos implicaciones: la directa ($\Rightarrow$) y la recíproca ($\Leftarrow$) {puddu2012conjuntos}.

### Implicación Directa ($\Rightarrow$): $\mathcal{P}(A) \subseteq \mathcal{P}(B) \Rightarrow A \subseteq B$

Supongamos que $\mathcal{P}(A) \subseteq \mathcal{P}(B)$. Queremos probar que para todo elemento $x \in A$, se cumple que $x \in B$.
1. Sea $x$ un elemento cualquiera de $A$ ($x \in A$).
2. Entonces $\{x\}$ es un subconjunto de $A$, lo que implica que $\{x\} \in \mathcal{P}(A)$.
3. Dado que por hipótesis $\mathcal{P}(A) \subseteq \mathcal{P}(B)$, se deduce que $\{x\} \in \mathcal{P}(B)$.
4. Por la definición de conjunto de partes, $\{x\} \in \mathcal{P}(B)$ implica que $\{x\} \subseteq B$.
5. Si el conjunto unitario $\{x\}$ está contenido en $B$, entonces su único elemento debe pertenecer a $B$. Por lo tanto, $x \in B$.
Como esto es válido para todo $x \in A$, concluimos que $A \subseteq B$.

### Implicación Recíproca ($\Leftarrow$): $A \subseteq B \Rightarrow \mathcal{P}(A) \subseteq \mathcal{P}(B)$

Supongamos que $A \subseteq B$. Queremos probar que para todo $S \in \mathcal{P}(A)$, se cumple que $S \in \mathcal{P}(B)$.
1. Sea $S \in \mathcal{P}(A)$ un elemento cualquiera de $\mathcal{P}(A)$.
2. Por definición de conjunto de partes, esto significa que $S \subseteq A$.
3. Tenemos ahora que $S \subseteq A$ y, por hipótesis, $A \subseteq B$.
4. Dado que la inclusión de conjuntos es una relación transitiva {uba2017fasciculo9}, de $S \subseteq A$ y $A \subseteq B$ se concluye que $S \subseteq B$.
5. Por la definición de conjunto de partes, $S \subseteq B$ implica que $S \in \mathcal{P}(B)$.
Como esto es válido para todo $S \in \mathcal{P}(A)$, concluimos que $\mathcal{P}(A) \subseteq \mathcal{P}(B)$.

$\square$
