---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 27
---

### Resolución

Sean $A=\{n\in\mathbb{N}/n\le92\}$ y $\mathcal{R}$ la relación en $A$:
$$x\mathcal{R}y \iff x^{2}-y^{2}=93x-93y$$

Manipulamos la ecuación definitoria:
$$x^2 - y^2 - 93x + 93y = 0 \iff (x-y)(x+y) - 93(x-y) = 0$$
Factoreando $(x-y)$:
$$(x-y)(x+y-93) = 0$$
Esta igualdad se cumple si y sólo si:
$$x=y \quad \text{ó} \quad x+y=93$$

#### i) Probar que $\mathcal{R}$ es una relación de equivalencia
- **Reflexividad**: $\forall x \in A$, se cumple $x=x$, por lo tanto $x\mathcal{R}x$.
- **Simetría**: Si $x\mathcal{R}y$, entonces $x=y$ o $x+y=93$. Como la igualdad y la suma son conmutativas, esto implica $y=x$ o $y+x=93$, luego $y\mathcal{R}x$.
- **Transitividad**: Sea $x\mathcal{R}y$ y $y\mathcal{R}z$. Tenemos cuatro casos:
  1. $x=y$ e $y=z \implies x=z \implies x\mathcal{R}z$.
  2. $x=y$ e $y+z=93 \implies x+z=93 \implies x\mathcal{R}z$.
  3. $x+y=93$ e $y=z \implies x+z=93 \implies x\mathcal{R}z$.
  4. $x+y=93$ e $y+z=93 \implies x=z \implies x\mathcal{R}z$.
En todos los casos se cumple $x\mathcal{R}z$.

**¿Es antisimétrica?**
No. Por ejemplo, $1\mathcal{R}92$ (pues $1+92=93$) y $92\mathcal{R}1$, pero $1 \neq 92$.

#### ii) Clase de equivalencia y cantidad de clases
La clase de equivalencia de un $x \in A$ es:
$$\bar{x} = \{y \in A : y=x \lor y=93-x\}$$
Como $1 \le x \le 92$, el valor $y = 93-x$ siempre está en el rango $[1, 92]$. Por ejemplo:
- Si $x=1$, $\bar{1} = \{1, 92\}$.
- Si $x=2$, $\bar{2} = \{2, 91\}$.
- ...
- Si $x=46$, $\bar{46} = \{46, 93-46\} = \{46, 47\}$.

Notamos que cada clase tiene exactamente 2 elementos y no hay ningún elemento tal que $x = 93-x$ (ya que $2x=93$ no tiene solución en $\mathbb{N}$).
Como el conjunto $A$ tiene 92 elementos y cada clase de equivalencia tiene 2 elementos, la cantidad de clases de equivalencia distintas es:
$$\text{Cant. Clases} = \frac{|A|}{2} = \frac{92}{2} = 46$$

---
**Cita:** {puddu2012conjuntos}
