---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 25
---

### Resolución

Sea $A=\{1,2,3,4,5,6,7,8,9,10\}$. Se nos da la partición $\mathcal{P} = \{C_1, C_2, C_3, C_4\}$ con:
- $C_1 = \{1, 3\}$
- $C_2 = \{2, 6, 7\}$
- $C_3 = \{4, 8, 9, 10\}$
- $C_4 = \{5\}$

#### 1. Construcción de la relación de equivalencia
La relación de equivalencia $\mathcal{R}$ asociada a una partición $\mathcal{P}$ se define como:
$$x\mathcal{R}y \iff \exists C \in \mathcal{P} \text{ tal que } x \in C \text{ e } y \in C$$
De forma equivalente, $\mathcal{R} = \bigcup_{C \in \mathcal{P}} (C \times C)$.
Por lo tanto, los pares de la relación son:
- De $C_1$: $\{(1,1), (1,3), (3,1), (3,3)\}$
- De $C_2$: $\{(2,2), (2,6), (2,7), (6,2), (6,6), (6,7), (7,2), (7,6), (7,7)\}$
- De $C_3$: $\{(4,4), (4,8), (4,9), (4,10), (8,4), (8,8), (8,9), (8,10), (9,4), (9,8), (9,9), (9,10), (10,4), (10,8), (10,9), (10,10)\}$
- De $C_4$: $\{(5,5)\}$

La relación completa es la unión de estos cuatro conjuntos de pares.

#### 2. Análisis de las clases de equivalencia
- **¿Cuántas clases de equivalencia distintas tiene?**
  Por definición, cada elemento de la partición es una clase de equivalencia. Como hay 4 conjuntos en la partición, la relación tiene **4 clases de equivalencia distintas**.
- **Representantes de cada clase:**
  Un representante es cualquier elemento perteneciente a la clase. Podemos elegir, por ejemplo, el menor elemento de cada conjunto:
  - Para $C_1$: representante **1**.
  - Para $C_2$: representante **2**.
  - Para $C_3$: representante **4**.
  - Para $C_4$: representante **5**.

#### 3. Gráfico de la relación
El gráfico consistirá en 4 componentes conexas (clanes completos):
- Un bloque con los nodos $\{1, 3\}$ todos conectados entre sí.
- Un bloque con los nodos $\{2, 6, 7\}$ todos conectados entre sí.
- Un bloque con los nodos $\{4, 8, 9, 10\}$ todos conectados entre sí.
- Un nodo aislado $\{5\}$ con un lazo sobre sí mismo.

---
**Cita:** {puddu2012conjuntos}
