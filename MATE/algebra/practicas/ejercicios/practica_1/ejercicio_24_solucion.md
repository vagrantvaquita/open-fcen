---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 24
---

### Resolución

Dada la relación de equivalencia $\mathcal{R}$ en $A=\{a,b,c,d,e,f\}$:
$$\mathcal{R}=\{(a,a),(b,b),(c,c),(d,d),(e,e),(f,f),(a,b),(b,a),(a,f),(f,a),(b,f),(f,b),(c,e),(e,c)\}$$

Recordamos que la clase de equivalencia de un elemento $x$, denotada $\bar{x}$, es el conjunto de todos los elementos de $A$ relacionados con él:
$$\bar{x} = \{y \in A : (x,y) \in \mathcal{R}\}$$

#### 1. Cálculo de las clases de equivalencia
- **Clase de $a$**: Buscamos todos los pares $(a, y) \in \mathcal{R}$.
  Observamos los pares: $(a,a), (a,b), (a,f)$.
  Por lo tanto: $\bar{a} = \{a, b, f\}$.
- **Clase de $b$**: Buscamos todos los pares $(b, y) \in \mathcal{R}$.
  Observamos los pares: $(b,b), (b,a), (b,f)$.
  Por lo tanto: $\bar{b} = \{a, b, f\}$.
  Notar que $\bar{b} = \bar{a}$, como es de esperar dado que $(a,b) \in \mathcal{R}$.
- **Clase de $c$**: Buscamos todos los pares $(c, y) \in \mathcal{R}$.
  Observamos los pares: $(c,c), (c,e)$.
  Por lo tanto: $\bar{c} = \{c, e\}$.
- **Clase de $d$**: Buscamos todos los pares $(d, y) \in \mathcal{R}$.
  Únicamente tenemos el par: $(d,d)$.
  Por lo tanto: $\bar{d} = \{d\}$.

#### 2. Partición asociada
La partición asociada a una relación de equivalencia es el conjunto cociente $A/\mathcal{R}$, que consiste en el conjunto de todas las clases de equivalencia distintas {puddu2012conjuntos}.
Las clases distintas halladas son:
- $C_1 = \{a, b, f\}$
- $C_2 = \{c, e\}$
- $C_3 = \{d\}$

Verificamos que forman una partición de $A$:
1. $C_i \neq \emptyset$ para todo $i$.
2. $C_1 \cap C_2 = \emptyset$, $C_1 \cap C_3 = \emptyset$, $C_2 \cap C_3 = \emptyset$.
3. $C_1 \cup C_2 \cup C_3 = \{a, b, f\} \cup \{c, e\} \cup \{d\} = \{a, b, c, d, e, f\} = A$.

Por lo tanto, la **partición asociada** es:
$$\mathcal{P} = \{\{a,b,f\}, \{c,e\}, \{d\}\}$$

---
**Cita:** {puddu2012conjuntos}
