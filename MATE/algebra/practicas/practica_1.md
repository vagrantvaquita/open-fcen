# Facultad de Ciencias Exactas y Naturales - UBA

## Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones

### I. Conjuntos

**1.** Dado el conjunto $A=\{1,2,3\}$, determinar cuáles de las siguientes afirmaciones son verdaderas:

* i) $1 \in A$
* ii) $\{1\} \subseteq A$
* iii) $\{2,1\} \subseteq A$
* iv) $\{1,3\} \in A$
* v) $\{2\} \in A$

**2.** Dado el conjunto $A=\{1,2,\{3\},\{1,2\}\}$, determinar cuáles de las siguientes afirmaciones son verdaderas:

* i) $3 \in A$
* ii) $\{3\} \subseteq A$
* iii) $\{3\} \in A$
* iv) $\{\{3\}\} \subseteq A$
* v) $\{1,2\} \in A$
* vi) $\{1,2\} \subseteq A$
* vii) $\{\{1,2\}\} \subseteq A$
* viii) $\{\{1,2\},3\} \subseteq A$
* ix) $\emptyset \in A$
* x) $\emptyset \subseteq A$
* xi) $A \in A$
* xii) $A \subseteq A$

**3.** Determinar si $A \subseteq B$ en cada uno de los siguientes casos:

* i) $A=\{1,2,3\}$, $B=\{5,4,3,2,1\}$
* ii) $A=\{1,2,3\}$, $B=\{1,2,\{3\},-3\}$
* iii) $A=\{x \in \mathbb{R} / 2 < |x| < 3\}$, $B=\{x \in \mathbb{R} / x^2 < 3\}$
* iv) $A=\{\emptyset\}$, $B=\emptyset$

**4.** Dados los subconjuntos $A=\{1,-2,7,3\}$, $B=\{1,\{3\},10\}$ y $C=\{-2,\{1,2,3\},3\}$ del conjunto referencial $V=\{1,\{3\},-2,7,10,\{1,2,3\},3\}$, hallar:

* i) $A \cap (B \triangle C)$
* ii) $(A \cap B) \triangle (A \cap C)$
* iii) $A^c \cap B^c \cap C^c$

**5.** Dados subconjuntos $A, B, C$ de un conjunto referencial $V$, describir $(A \cup B \cup C)^c$ en términos de intersecciones y complementos, y $(A \cap B \cap C)^c$ en términos de uniones y complementos.

**6.** Sean $A, B$ y $C$ conjuntos. Representar en un diagrama de Venn:

* i) $(A \cup B^c) \cap C$
* ii) $A \triangle (B \cup C)$
* iii) $A \cup (B \triangle C)$

**7.** Encontrar fórmulas que describan las partes rayadas de los diagramas de Venn, utilizando únicamente intersecciones, uniones y complementos.

**8.** Hallar el conjunto $\mathcal{P}(A)$ de partes de $A$ en los casos:

* i) $A=\{1\}$
* ii) $A=\{a,b\}$
* iii) $A=\{1,\{1,2\},3\}$

**9.** Sean $A$ y $B$ conjuntos. Probar que $\mathcal{P}(A) \subseteq \mathcal{P}(B) \iff A \subseteq B$.

---

### II. Lógica y Demostraciones

**10.** Sean $p, q$ proposiciones. Verificar que las siguientes expresiones tienen la misma tabla de verdad para concluir que son equivalentes:

* i) $p \Rightarrow q$, $\sim q \Rightarrow \sim p$, $\sim p \vee q$ y $\sim (p \wedge \sim q)$.
* ii) $\sim (p \Rightarrow q)$ y $p \wedge \sim q$.

Cuando para probar $p \Rightarrow q$ se prueba en su lugar $\sim q \Rightarrow \sim p$ se dice que es una demostración
por contrarrecíproco, mientras que cuando se prueba en su lugar que suponer que vale $p \wedge \sim q$
lleva a una contradicción, se dice que es una demostración por reducción al absurdo.

**11.** Hallar contraejemplos para mostrar que las siguientes proposiciones son falsas:

* i) $\forall n \in \mathbb{N}, n$ no es un número entero.
* ii) $\forall x,y \in \mathbb{R}$ con $x, y$ positivos, $\sqrt{x+y} = \sqrt{x} + \sqrt{y}$.
* iii) $\forall x \in \mathbb{R}, x^2 > 4 \Rightarrow x > 2$.

**12.** i) Decidir si las siguientes proposiciones son verdaderas o falsas, justificando debidamente:

* (a) $\forall n \in \mathbb{N}, n \ge 5 \vee n \le 8$
* (b) $\exists n \in \mathbb{N} / n \ge 5 \wedge n \le 8$
* (c) $\forall n \in \mathbb{N}, \exists m \in \mathbb{N} / m > n$
* (d) $\exists n \in \mathbb{N} / \forall m \in \mathbb{N}, m > n$
* (e) $\forall x \in \mathbb{R}, x > 3 \Rightarrow x^2 > 4$
* (f) Si $z$ es un número real, entonces $z$ es un número complejo.

ii) Negar las proposiciones anteriores, y en cada caso verificar que la proposición negada tiene el
valor de verdad opuesto al de la original.

iii) Reescribir (e) y (f) utilizando las equivalencias del ejercicio 10i).

**13.** Determinar cuáles de las siguientes afirmaciones son verdaderas cualesquiera sean los subconjuntos $A$, $B$ y $C$ de un conjunto referencial $V$ y cuáles no. Para las que sean verdaderas, dar una demostración, para las otras dar un contraejemplo.

* i) $(A \triangle B) - C = (A - C) \triangle (B - C)$
* ii) $(A \cap B) \triangle C = (A \triangle C) \cap (B \triangle C)$
* iii) $C \subseteq A \Rightarrow B \cap C \subseteq (A \triangle B)^c$
* iv) $A \triangle B = \emptyset \iff A = B$

**14.** Sean $A$, $B$ y $C$ subconjuntos de un conjunto referencial $V$ . Probar que

* i) $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$
* ii) $A - (B - C) = (A - B) \cup (A \cap C)$
* iii) $A \triangle B \subseteq (A \triangle C) \cup (B \triangle C)$
* iv) $(A \cap C) - B = (A - B) \cap C$
* v) $A \subseteq B \Rightarrow A \triangle B = B \cap A^c$
* vi) $A \subseteq B \iff B^c \subseteq A^c$
* vii) $A \cap C = \emptyset \Rightarrow A \cap (B \triangle C) = A \cap B$

**15.** Sean $A=\{1,2,3\}$, $B=\{1,3,5,7\}$. Hallar $A \times A$, $A \times B$, $(A \cap B) \times (A \cup B)$.

**16.** Sean $A, B$ y $C$ conjuntos. Probar que:

* i) $(A \cup B) \times C = (A \times C) \cup (B \times C)$
* ii) $(A \cap B) \times C = (A \times C) \cap (B \times C)$
* iii) $(A - B) \times C = (A \times C) - (B \times C)$
* iv) $(A \triangle B) \times C = (A \times C) \triangle (B \times C)$

**17.** Sean $A=\{1,2,3\}$ y $B=\{1,3,5,7\}$. Verificar si las siguientes son relaciones de $A$ en $B$:

* i) $\mathcal{R} = \{(1,1), (1,3), (1,7), (3,1), (3,5)\}$
* ii) $\mathcal{R} = \{(1,1), (1,3), (2,7), (3,2), (3,5)\}$
* iii) $\mathcal{R} = \{(1,1), (2,7), (3,7)\}$
* iv) $\mathcal{R} = \{(1,3), (2,1), (3,7)\}$

---

### III. Relaciones

**18.** Sean $A=\{1,2,3\}$ y $B=\{1,3,5,7\}$. Describir por extensión cada una de las relaciones siguientes de $A$ en $B$:

* i) $(a,b) \in \mathcal{R} \iff a \le b$
* ii) $(a,b) \in \mathcal{R} \iff a > b$
* iii) $(a,b) \in \mathcal{R} \iff a \cdot b$ es par
* iv) $(a,b) \in \mathcal{R} \iff a+b > 6$

**19.** Sea $A=\{a,b,c,d,e,f,g,h\}$. Para cada gráfico, describir por extensión la relación y determinar si es reflexiva, simétrica, antisimétrica o transitiva.

**20.** Sea $A=\{1,2,3,4,5,6\}$. Graficar la relación. Determinar si es reflexiva, simétrica, antisimétrica o
transitiva.

$$
\mathcal{R}=\{(1,1),(1,3),(3,1),(3,3),(6,4),(4,6),(4,4),(6,6)\}
$$

**21.** Sea $A=\{a,b,c,d,e,f\}$ y sea $R$ una relación en $A$. Hallar la mínima cantidad de pares a agregar para que sea:

* i) reflexiva
* ii) simétrica
* iii) transitiva
* iv) reflexiva y simétrica
* v) simétrica y transitiva
* vi) de equivalencia.

**22.** En cada uno de los siguientes casos determinar si l determinar si la relación $\mathcal{R}$ en $A$ es reflexiva, simétrica, antisimétrica, transitiva, de equivalencia o de orden:

* i) $A=\{1,2,3,4,5\}$, $\mathcal{R} = \{(1,1), (2, 2), (3, 3), (4, 4), (5, 5), (1, 2), (1, 3), (2, 5), (1,5)\}$
* ii) $A=\mathbb{N}$, $\mathcal{R}=\{(a,b)\in\mathbb{N}\times\mathbb{N} / a+b \text{ es par}\}$
* iii) $A=\mathbb{Z}$, $\mathcal{R}=\{(a,b)\in\mathbb{Z}\times\mathbb{Z} / |a|\le|b|\}$
* iv) $A=\mathbb{Z}$, $\mathcal{R}$ definida por $a\mathcal{R}b \iff b$ es múltiplo de $a$
* v) $A=\mathcal{P}(\mathbb{R})$, $\mathcal{R}$ definida por $X\mathcal{R}Y \iff X\cap\{1,2,3\}\subseteq Y\cap\{1,2,3\}$
* vi) $A=\mathcal{P}(\{n\in\mathbb{N} / n\le30\})$, $\mathcal{R}$ definida por $X\mathcal{R}Y \iff 2 \notin X\cap Y^c$
* vii) $A=\mathbb{N}\times\mathbb{N}$, $\mathcal{R}$ definida por $(a, b) \mathcal{R} (c,d) \iff bc$ es múltiplo de $ad$

**23.** Sea $A$ un conjunto. Describir todas las relaciones en $A$ que son a la vez:

* i) simétricas y antisimétricas.
* ii) de equivalencia y de orden.

¿Puede una relación en A no ser ni simétrica ni antisimétrica?

**24.** Sea $A=\{a,b,c,d,e,f\}$. Dada la relación de equivalencia en $A$:

$$
\mathcal{R}=\{(a,a),(b,b),(c,c),(d,d),(e,e),(f,f),(a,b),(b,a),(a,f),(f,a),(b,f),(f,b),(c,e),(e,c)\}
$$

Hallar las clases $\bar{a}, \bar{b}, \bar{c}, \bar{d}$ y la partición asociada.

Hallar la clase $\bar{a}$ de $a$, la clase $\bar{b}$ de $b$, la clase $\bar{c}$ de $c$, la clase $\bar{d}$ de $d$, y la partición asociada a $R$.

**25.** Sea $A=\{1,2,3,4,5,6,7,8,9,10\}$. Hallar y graficar la relación de equivalencia en $A$ asociada a la partición $\{\{1,3\}, \{2, 6, 7\}, \{4, 8, 9, 10\}, \{5\}\}$. ¿Cuántas clases de equivalencia distintas tiene? Hallar un representante para cada clase.

**26.** Sean $P=\mathcal{P}(\{1,2,3,4,5,6,7,8,9,10\})$ el conjunto de partes de $\{1,...,10\}$ y $\mathcal{R}$ la relación en $P$ definida por
$$A\mathcal{R}B \iff (A\triangle B)\cap\{1,2,3\}=\emptyset$$

* i) Probar que $\mathcal{R}$ es una relación de equivalencia y decidir si es antisimétrica (Sugerencia: usar adecuadamente el ejercicio 14iii)).
* ii) Hallar la clase de equivalencia de $A=\{1,2,3\}$.

**27.** Sean $A=\{n\in\mathbb{N}/n\le92\}$ y $\mathcal{R}$ la relación en $A$ definida por
$$x\mathcal{R}y\iff x^{2}-y^{2}=93x-93y$$
i) Probar que $\mathcal{R}$ es una relación de equivalencia ¿Es antisimétrica?
ii) Hallar la clase de equivalencia de cada $x\in A$ Deducir cuántas clases de equivalencia distintas determina la relación $\mathcal{R}$.

**28.**

* i) Sea $A=\{1,2,3,4,5,6,7,8,9,10\}$. Consideremos en $\mathcal{P}(A)$ la relación de equivalencia dada por el cardinal (es decir, la cantidad de elementos): dos subconjuntos de $A$ están relacionados si y solo si tienen la misma cantidad de elementos ¿Cuántas clases de equivalencia distintas determina la relación? Hallar un representante para cada clase.

* ii) En el conjunto de todos los subconjuntos finitos de $\mathbb{N}$, consideremos nuevamente la relación de equivalencia dada por el cardinal: dos subconjuntos finitos de $\mathbb{N}$ están relacionados si y solo si tienen la misma cantidad de elementos ¿Cuántas clases de equivalencia distintas determina la relación? Hallar un representante para cada clase.

---

### IV. Funciones

**29.** Determinar si $\mathcal{R}$ es función de $A$ en $B$ en los casos:

* ii) $A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,a),(4,b),(5,c),(3,d)\}$
* iii) $A=\{1,2,3,4,5\}, B=\{a,b,c,d\}, \mathcal{R}=\{(1,a),(2,a),(3,d),(4,b),(5,c)\}$
* iv) $A=\mathbb{N}$, $B=\mathbb{R},$ $\mathcal{R}=\{(a,b)\in\mathbb{N}\times\mathbb{R}/a=2b-3\}$
* v) $A=\mathbb{R},$ $B=\mathbb{N}$, $\mathcal{R}=\{(a,b)\in\mathbb{R}\times\mathbb{N}/a=2b-3\}$
* vi) $A=\mathbb{Z}$, $B=\mathbb{Z}$ $\mathcal{R}=\{(a,b)\in\mathbb{Z}\times\mathbb{Z}/a+b$ es divisible por 5\}

**30.** Determinar si las siguientes funciones son inyectivas, sobreyectivas o biyectivas:

* i) $f: \mathbb{R} \longrightarrow \mathbb{R}$, $f(x) = 12x^2 - 5$
* ii) $f: \mathbb{R}^2 \longrightarrow \mathbb{R}$, $f(x,y) = x + y$
* iii) $f: \mathbb{R}^3 \longrightarrow \mathbb{R}^2$, $f(x,y,z) = (x+y, 2z)$
* iv) $f:\mathbb{N}\longrightarrow\mathbb{N}$, $f(n)=\begin{cases} \frac{n}{2} & \text{si } n \text{ es par} \\ n+1 & \text{si } n \text{ es impar} \end{cases}$
* v) $f:\mathbb{Z}\times\mathbb{Z}\longrightarrow\mathbb{Z},$ $f(a,b)=3a-2b$
* vi) $f:\mathbb{Z}\rightarrow\mathbb{N}$ $f(a)=\begin{cases}2a&si~a>0\\ 1-2a&si~a\le0\end{cases}$

**31.**

* i) Dadas las funciones

$$
f: \mathbb{N} \to \mathbb{N}, f(n) = \begin{cases} \frac{n}{6} & \text{si } n \text{ es divisible por 6} \\ 3n+1 & \text{en los otros casos} \end{cases}
$$

$$
g:\mathbb{N}\times\mathbb{N}\rightarrow\mathbb{N}, g(n,m)=n(m+1)
$$

calcular, de ser posible, $(f\circ g)(3,4)$, $(f\circ g)(2,5) y (f\circ g)(3,2)$

* ii) Dadas las funciones
$$
f: \mathbb{R} \to \mathbb{R}, f(x) = \begin{cases} x^2 & \text{si } x < 7 \\ 2x-1 & \text{si } x \ge 7 \end{cases}
$$

$$
g: \mathbb{N} \to \mathbb{R}, g(n)=\sqrt{n}
$$

hallar, si existen, todos los $n\in\mathbb{N}$ tales que $(f\circ g)(n)=13$ y todos los $m\in\mathbb{N}$ tales que $(f\circ g)(m)=15$.

**32.** Hallar $f \circ g$ y $g \circ f$ en los siguientes casos:

* i) $f: \mathbb{R} \to \mathbb{R}, f(x) = 2x^{2}-18$ y $g: \mathbb{R} \to \mathbb{R}, g(x) = x+3$
* ii) $f, g: \mathbb{N} \to \mathbb{N}$ con $f(n) = \begin{cases} n-2 & \text{si } n \text{ es divisible por } 4 \\ n+1 & \text{si } n \text{ no es divisible por } 4 \end{cases}$ y $g(n) = 4n$
* iii) $f: \mathbb{R} \to \mathbb{R} \times \mathbb{R}, f(x) = (x+5, 3x)$ y $g: \mathbb{N} \to \mathbb{R}, g(n) = \sqrt{n}$

**33.** Hallar dos funciones $f, g: \mathbb{N} \to \mathbb{N}$ tales que $f \circ g = id_{\mathbb{N}}$ y $g \circ f \ne id_{\mathbb{N}}$, donde $id_{\mathbb{N}}: \mathbb{N} \to \mathbb{N}$ denota la función identidad del conjunto $\mathbb{N}$.

**34.** Sean $A, B$ y $C$ conjuntos. Probar que si $f: B \to C$ y $g: A \to B$ son funciones entonces valen

* i) si $f \circ g$ inyectiva entonces $g$ es inyectiva.
* ii) si $f \circ g$ sobreyectiva entonces $f$ es sobreyectiva.
* iii) si $f$ y $g$ son inyectivas entonces $f \circ g$ es inyectiva.
* iv) si $f$ y $g$ son sobreyectivas entonces $f \circ g$ es sobreyectiva.
* v) si $f$ y $g$ son biyectivas entonces $f \circ g$ es biyectiva.

**35.** Sea $F = \{f: \{1,...,10\} \to \{1,...,10\} / f \text{ es una función biyectiva} \}$, y sea $\mathcal{R}$ la relación en $F$ definida por

$$f\mathcal{R}g \iff \exists n \in \{1,...,10\} / f(n) = 1 \text{ y } g(n) = 1$$

* i) Probar que $\mathcal{R}$ es una relación de equivalencia ¿Es antisimétrica?
* ii) Sea $Id: \{1,...,10\} \to \{1,...,10\}$ la función identidad, o sea, $Id(n)=n$ $\forall n \in \{1,...,10\}$. Dar tres elementos distintos de la clase de equivalencia de $Id$.

Importante: al exhibir una función es indispensable definirla en todos los elementos de su dominio.

**36.** Sea $f: \{1,2,3,4\} \to \{1,2,3,4\}$ una función. Consideremos el conjunto de todas las funciones de $\{1,2,3,4\}$ en $\{1, 2, 3, 4, 5, 6, 7, 8\}$, es decir,
$$\mathcal{F}=\{g:\{1,2,3,4\}\longrightarrow\{1,2,3,4,5,6,7,8\}\}$$
y definimos sobre $\mathcal{F}$ la relación dada por
$$g\mathcal{R}h \iff g \circ f = h \circ f$$

i) Probar que $\mathcal{R}$ es una relación de equivalencia ¿Es siempre antisimétrica (sin importar cómo sea $f$)?

ii) Asumiendo que $f$ es sobreyectiva, calcular la clase de equivalencia de cada $g \in \mathcal{F}$.
