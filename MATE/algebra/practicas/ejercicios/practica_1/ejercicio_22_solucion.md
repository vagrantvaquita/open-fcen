---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Relaciones
practica: 1
ejercicio: 22
---

Analizaremos cada relación según las definiciones de reflexividad (R), simetría (S), antisimetría (AS) y transitividad (T) para clasificar cada una como relación de equivalencia (E) o de orden (O) {puddu2012conjuntos}.

### i) $A=\{1,2,3,4,5\}$, $\mathcal{R} = \{(1,1), (2, 2), (3, 3), (4, 4), (5, 5), (1, 2), (1, 3), (2, 5), (1,5)\}$
- **R:** Sí, todos los $(x,x)$ están presentes.
- **S:** No, $(1,2) \in \mathcal{R}$ pero $(2,1) \notin \mathcal{R}$.
- **AS:** Sí, no hay pares $(x,y)$ y $(y,x)$ con $x \neq y$.
- **T:** Sí, $(1,2)$ y $(2,5)$ están, y también $(1,5)$.
- **Conclusión:** Es una **relación de orden**.

### ii) $A=\mathbb{N}$, $\mathcal{R}=\{(a,b)\in\mathbb{N}\times\mathbb{N} / a+b \text{ es par}\}$
- **R:** Sí, $a+a = 2a$ es siempre par.
- **S:** Sí, si $a+b$ es par, entonces $b+a$ es par.
- **AS:** No, $1+3$ es par y $3+1$ es par, pero $1 \neq 3$.
- **T:** Sí. Si $a+b$ y $b+c$ son pares, $a$ y $b$ tienen la misma paridad, y $b$ y $c$ también. Por ende, $a$ y $c$ tienen la misma paridad $\implies a+c$ es par.
- **Conclusión:** Es una **relación de equivalencia**.

### iii) $A=\mathbb{Z}$, $\mathcal{R}=\{(a,b)\in\mathbb{Z}\times\mathbb{Z} / |a|\le|b|\}$
- **R:** Sí, $|a| \le |a|$.
- **S:** No, $|1| \le |2|$ pero $|2| \not\le |1|$.
- **AS:** No, $|1| \le |-1|$ y $|-1| \le |1|$ pero $1 \neq -1$.
- **T:** Sí, $|a| \le |b| \land |b| \le |c| \implies |a| \le |c|$.
- **Conclusión:** Es una relación de pre-orden (no es de equivalencia ni de orden parcial).

### iv) $A=\mathbb{Z}$, $a\mathcal{R}b \iff b$ es múltiplo de $a$ ($a|b$)
- **R:** Sí, $a|a$ para todo $a \in \mathbb{Z}$.
- **S:** No, $1|2$ pero $2 \not| 1$.
- **AS:** No en $\mathbb{Z}$, pues $1|(-1)$ y $(-1)|1$ pero $1 \neq -1$. (Sería de orden en $\mathbb{N}$).
- **T:** Sí, $a|b \land b|c \implies a|c$.
- **Conclusión:** Ni de equivalencia ni de orden.

### v) $A=\mathcal{P}(\mathbb{R})$, $X\mathcal{R}Y \iff X\cap\{1,2,3\}\subseteq Y\cap\{1,2,3\}$
- **R:** Sí, $X\cap C \subseteq X\cap C$.
- **S:** No.
- **AS:** No, si $X=\{4\}$ y $Y=\{5\}$, ambos intersecan $\{1,2,3\}$ en $\emptyset$, cumpliendo $X\mathcal{R}Y$ y $Y\mathcal{R}X$, pero $X \neq Y$.
- **T:** Sí, por transitividad de la inclusión.
- **Conclusión:** Ni de equivalencia ni de orden.

### vi) $A=\mathcal{P}(\{n\in\mathbb{N} / n\le30\})$, $X\mathcal{R}Y \iff 2 \notin X\cap Y^c$
Notar que $2 \notin X \cap Y^c \iff \neg(2 \in X \land 2 \notin Y) \iff 2 \in X \implies 2 \in Y$.
- **R:** Sí, $2 \in X \implies 2 \in X$.
- **S:** No, si $2 \notin X$ y $2 \in Y$, se cumple $X\mathcal{R}Y$ pero no $Y\mathcal{R}X$.
- **AS:** No, si $2 \notin X$ y $2 \notin Y$, se cumple la condición en ambos sentidos para cualquier par de conjuntos que no contengan al $2$.
- **T:** Sí, $(P \implies Q) \land (Q \implies R) \implies (P \implies R)$.
- **Conclusión:** Ni de equivalencia ni de orden.

### vii) $A=\mathbb{N}\times\mathbb{N}$, $(a, b) \mathcal{R} (c,d) \iff bc$ es múltiplo de $ad$ ($ad|bc$)
La condición es equivalente a $\frac{b}{a}$ es múltiplo de $\frac{d}{c}$? No. Es $\frac{b}{a} / \frac{d}{c} \in \mathbb{Z}$.
Sea $q((a,b)) = b/a$. Entonces $(a,b)\mathcal{R}(c,d) \iff q(c,d) | q(a,b)$? No, es $ad|bc \iff \frac{bc}{ad} \in \mathbb{Z} \iff \frac{b}{a} \cdot \frac{c}{d} \in \mathbb{Z}$? No.
$bc = k ad \iff \frac{b}{a} = k \frac{d}{c}$.
- **R:** $(a,b)\mathcal{R}(a,b) \iff ab$ múltiplo de $ab$ (Sí).
- **S:** No.
- **AS:** No, $(1,2)\mathcal{R}(2,4)$ pues $2\cdot 2 = 1 \cdot 4$ ($k=1$), y $(2,4)\mathcal{R}(1,2)$ ($k=1$), pero $(1,2) \neq (2,4)$.
- **T:** Sí. Si $bc = k_1 ad$ y $de = k_2 cf$, entonces $bcde = k_1 k_2 adcf \implies be = k_1 k_2 af$.
- **Conclusión:** Ni de equivalencia ni de orden.

---
**Cita:** {puddu2012conjuntos}
