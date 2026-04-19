---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 23
---

### Resolución

#### i) Relaciones simétricas y antisimétricas
Sea $\mathcal{R}$ una relación en $A$.
- Por ser **simétrica**: $\forall x, y \in A, (x,y) \in \mathcal{R} \implies (y,x) \in \mathcal{R}$.
- Por ser **antisimétrica**: $\forall x, y \in A, ((x,y) \in \mathcal{R} \land (y,x) \in \mathcal{R}) \implies x=y$.

Combinando ambas condiciones, si $(x,y) \in \mathcal{R}$, por simetría $(y,x) \in \mathcal{R}$, y por antisimetría esto implica que $x=y$.
Esto significa que los únicos pares posibles en $\mathcal{R}$ son de la forma $(x,x)$.
Por lo tanto, las relaciones que cumplen ambas propiedades son todos los **subconjuntos de la relación identidad** (o diagonal):
$$\mathcal{R} \subseteq \Delta_A = \{(x,x) : x \in A\}$$

#### ii) Relaciones de equivalencia y de orden
- Una **relación de equivalencia** es reflexiva, simétrica y transitiva.
- Una **relación de orden** es reflexiva, antisimétrica y transitiva.

Para que una relación cumpla ambas, debe ser reflexiva, simétrica, antisimétrica y transitiva.
Por el inciso anterior, al ser simétrica y antisimétrica, debe cumplirse que $\mathcal{R} \subseteq \Delta_A$.
Además, por ser **reflexiva**, debe contener a todos los pares $(x,x)$ para todo $x \in A$, es decir, $\Delta_A \subseteq \mathcal{R}$.
Por lo tanto, la única relación que es simultáneamente de equivalencia y de orden es la **relación identidad**:
$$\mathcal{R} = \{(x,x) : x \in A\}$$

#### iii) ¿Puede una relación no ser ni simétrica ni antisimétrica?
Sí. Para que no sea simétrica, debe existir al menos un par $(x,y) \in \mathcal{R}$ tal que $(y,x) \notin \mathcal{R}$ (con $x \neq y$).
Para que no sea antisimétrica, deben existir $x, y \in A$ con $x \neq y$ tales que $(x,y) \in \mathcal{R}$ y $(y,x) \in \mathcal{R}$.
**Ejemplo:** Sea $A=\{1,2,3\}$ y la relación:
$$\mathcal{R} = \{(1,2), (2,1), (1,3)\}$$
- **No es simétrica** porque $(1,3) \in \mathcal{R}$ pero $(3,1) \notin \mathcal{R}$.
- **No es antisimétrica** porque $(1,2) \in \mathcal{R}$ y $(2,1) \in \mathcal{R}$, pero $1 \neq 2$.

---
**Cita:** {puddu2012conjuntos}
