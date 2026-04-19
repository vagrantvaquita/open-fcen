---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 20
---

### Análisis de Propiedades

Sea $A=\{1,2,3,4,5,6\}$. La relación dada es:
$$\mathcal{R}=\{(1,1),(1,3),(3,1),(3,3),(6,4),(4,6),(4,4),(6,6)\}$$

Para determinar las propiedades, analizamos cada definición formal según {puddu2012conjuntos}:

#### 1. Reflexividad
Una relación $\mathcal{R}$ es reflexiva en $A$ si $\forall x \in A, (x,x) \in \mathcal{R}$.
En este caso, observamos que elementos como $2, 5 \in A$ no cumplen la condición:
$$(2,2) \notin \mathcal{R} \quad \text{y} \quad (5,5) \notin \mathcal{R}$$
Por lo tanto, **$\mathcal{R}$ no es reflexiva**.

#### 2. Simetría
$\mathcal{R}$ es simétrica si $\forall x, y \in A, (x,y) \in \mathcal{R} \implies (y,x) \in \mathcal{R}$.
Verificamos los pares no diagonales:
- $(1,3) \in \mathcal{R} \implies (3,1) \in \mathcal{R}$ (se cumple)
- $(6,4) \in \mathcal{R} \implies (4,6) \in \mathcal{R}$ (se cumple)
Los pares diagonales siempre cumplen la simetría.
Por lo tanto, **$\mathcal{R}$ es simétrica**.

#### 3. Antisimetría
$\mathcal{R}$ es antisimétrica si $\forall x, y \in A, ((x,y) \in \mathcal{R} \land (y,x) \in \mathcal{R}) \implies x=y$.
Observamos que:
$$(1,3) \in \mathcal{R} \quad \text{y} \quad (3,1) \in \mathcal{R}, \text{ pero } 1 \neq 3$$
Por lo tanto, **$\mathcal{R}$ no es antisimétrica**.

#### 4. Transitividad
$\mathcal{R}$ es transitiva si $\forall x, y, z \in A, ((x,y) \in \mathcal{R} \land (y,z) \in \mathcal{R}) \implies (x,z) \in \mathcal{R}$.
Analicemos los bloques de elementos relacionados:
- Para $\{1,3\}$: Tenemos todos los pares posibles $\{(1,1), (1,3), (3,1), (3,3)\}$, lo cual es una relación de equivalencia sobre el subconjunto $\{1,3\}$ y por ende es transitiva.
- Para $\{4,6\}$: Tenemos todos los pares posibles $\{(4,4), (4,6), (6,4), (6,6)\}$, que también es transitiva.
No hay otros pares que "conecten" elementos fuera de estos bloques.
Por lo tanto, **$\mathcal{R}$ es transitiva**.

### Gráfico de la relación (Diagrama de Venn/Grafo)
La relación puede representarse como un conjunto de nodos con flechas (o aristas en caso de simetría):
- Un lazo en los nodos $1, 3, 4, 6$.
- Una flecha doble entre $1$ y $3$.
- Una flecha doble entre $4$ y $6$.
- Los nodos $2$ y $5$ quedan aislados (sin flechas).

---
**Cita:** {puddu2012conjuntos}
