---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 12
---

# Solución del Ejercicio 12

Para decidir el valor de verdad de proposiciones cuantificadas, aplicaremos las definiciones de los cuantificadores universal ($\forall$) y existencial ($\exists$) {puddu2012conjuntos}.

### Decisión de Valor de Verdad y Justificación

* **(a) $\forall n \in \mathbb{N}, n \ge 5 \vee n \le 8$:** **Verdadero**. Para que la disyunción sea falsa, ambas condiciones deben ser falsas. Para que $n < 5$ y $n > 8$ simultáneamente, el número debería ser, por ejemplo, $4$ y $9$ al mismo tiempo, lo cual es imposible. Cualquier número natural cumple al menos una de las dos condiciones.
* **(b) $\exists n \in \mathbb{N} / n \ge 5 \wedge n \le 8$:** **Verdadero**. Basta con encontrar un ejemplo. El número $n=6$ es un natural y cumple $6 \ge 5$ y $6 \le 8$.
* **(c) $\forall n \in \mathbb{N}, \exists m \in \mathbb{N} / m > n$:** **Verdadero**. Dado cualquier $n \in \mathbb{N}$, el número $m = n + 1$ es un natural y satisface $m > n$. Esto expresa que el conjunto $\mathbb{N}$ no tiene cota superior.
* **(d) $\exists n \in \mathbb{N} / \forall m \in \mathbb{N}, m > n$:** **Falso**. Si tal $n$ existiera, al tomar $m = n$ (que es un natural), la proposición exigiría que $n > n$, lo cual es una contradicción.
* **(e) $\forall x \in \mathbb{R}, x > 3 \Rightarrow x^2 > 4$:** **Verdadero**. Si $x > 3$, entonces $x$ es positivo, por lo que podemos elevar al cuadrado manteniendo el orden: $x^2 > 3^2 = 9$. Como $9 > 4$, por transitividad $x^2 > 4$.
* **(f) Si $z \in \mathbb{R} \Rightarrow z \in \mathbb{C}$:** **Verdadero**. Por definición, el conjunto de los números complejos contiene a los reales ($\mathbb{R} \subseteq \mathbb{C}$) {uba2017fasciculo9}.

### i) Negaciones y Valor de Verdad

Utilizamos las reglas de De Morgan para cuantificadores ($\sim \forall x, P(x) \equiv \exists x, \sim P(x)$ y viceversa):

* **$\sim$(a): $\exists n \in \mathbb{N} / n < 5 \wedge n > 8$**. **Falso**. No hay naturales menores a 5 y mayores a 8 simultáneamente.
* **$\sim$(b): $\forall n \in \mathbb{N}, n < 5 \vee n > 8$**. **Falso**. Un contraejemplo es $n=6$.
* **$\sim$(c): $\exists n \in \mathbb{N} / \forall m \in \mathbb{N}, m \le n$**. **Falso**. Esto diría que existe un natural máximo.
* **$\sim$(d): $\forall n \in \mathbb{N}, \exists m \in \mathbb{N} / m \le n$**. **Verdadero**. Para cualquier $n$, basta tomar $m=n$.
* **$\sim$(e): $\exists x \in \mathbb{R} / x > 3 \wedge x^2 \le 4$**. **Falso**. Ya probamos que si $x > 3$, $x^2 > 9$.
* **$\sim$(f): $\exists z \in \mathbb{R} / z \notin \mathbb{C}$**. **Falso**. Ya que $\mathbb{R} \subseteq \mathbb{C}$.

### ii) Reescribir (e) y (f) usando equivalencias

Recordamos: $p \Rightarrow q \equiv \sim q \Rightarrow \sim p \equiv \sim p \vee q$.

* **(e) $\forall x \in \mathbb{R}, x > 3 \Rightarrow x^2 > 4$**:
    - **Contrarrecíproco:** $\forall x \in \mathbb{R}, x^2 \le 4 \Rightarrow x \le 3$.
    - **Disyunción:** $\forall x \in \mathbb{R}, x \le 3 \vee x^2 > 4$.
* **(f) Si $z \in \mathbb{R} \Rightarrow z \in \mathbb{C}$**:
    - **Contrarrecíproco:** Si $z \notin \mathbb{C}$, entonces $z \notin \mathbb{R}$.
    - **Disyunción:** $z \notin \mathbb{R}$ o $z \in \mathbb{C}$.
