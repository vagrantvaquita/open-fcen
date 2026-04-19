---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Funciones
practica: 1
ejercicio: 30
---

# Ejercicio 30

Determinar si las siguientes funciones son inyectivas, sobreyectivas o biyectivas:

* i) $f: \mathbb{R} \longrightarrow \mathbb{R}$, $f(x) = 12x^2 - 5$
* ii) $f: \mathbb{R}^2 \longrightarrow \mathbb{R}$, $f(x,y) = x + y$
* iii) $f: \mathbb{R}^3 \longrightarrow \mathbb{R}^2$, $f(x,y,z) = (x+y, 2z)$
* iv) $f:\mathbb{N}\longrightarrow\mathbb{N}$, $f(n)=\begin{cases} \frac{n}{2} & \text{si } n \text{ es par} \\ n+1 & \text{si } n \text{ es impar} \end{cases}$
* v) $f:\mathbb{Z}\times\mathbb{Z}\longrightarrow\mathbb{Z},$ $f(a,b)=3a-2b$
* vi) $f:\mathbb{Z}\rightarrow\mathbb{N}$ $f(a)=\begin{cases}2a&si~a>0\\ 1-2a&si~a\le0\end{cases}$

## Resolución

### i) $f(x) = 12x^2 - 5$
- **Inyectividad:** Una función es inyectiva si $f(x_1) = f(x_2) \implies x_1 = x_2$. Aquí, $f(1) = 12(1)^2 - 5 = 7$ y $f(-1) = 12(-1)^2 - 5 = 7$. Como $f(1) = f(-1)$ pero $1 \neq -1$, **no es inyectiva**.
- **Sobreyectividad:** Una función es sobreyectiva si su imagen es igual al conjunto de llegada ($\mathbb{R}$). Dado que $x^2 \ge 0$ para todo $x \in \mathbb{R}$, entonces $12x^2 \ge 0$ y $f(x) \ge -5$. La imagen de $f$ es $[-5, +\infty)$, que no es igual a $\mathbb{R}$. **No es sobreyectiva**.
- **Biyectividad:** Como no es inyectiva ni sobreyectiva, **no es biyectiva**.

### ii) $f(x,y) = x + y$
- **Inyectividad:** $f(1, 0) = 1+0 = 1$ y $f(0, 1) = 0+1 = 1$. Como $(1,0) \neq (0,1)$, **no es inyectiva**.
- **Sobreyectividad:** Sea $z \in \mathbb{R}$. Queremos ver si existe $(x,y) \in \mathbb{R}^2$ tal que $x+y=z$. Podemos tomar, por ejemplo, $x=z$ e $y=0$. Entonces $f(z, 0) = z$. **Es sobreyectiva**.
- **Biyectividad:** **No es biyectiva**.

### iii) $f(x,y,z) = (x+y, 2z)$
- **Inyectividad:** $f(1, 0, 0) = (1, 0)$ y $f(0, 1, 0) = (1, 0)$. Como $(1,0,0) \neq (0,1,0)$, **no es inyectiva**.
- **Sobreyectividad:** Sea $(u, v) \in \mathbb{R}^2$. Buscamos $(x,y,z)$ tal que $x+y=u$ y $2z=v$. Podemos elegir $z = v/2$, $x = u$ e $y = 0$. Como siempre existen tales valores en $\mathbb{R}$, **es sobreyectiva**.
- **Biyectividad:** **No es biyectiva**.

### iv) $f(n)=\begin{cases} n/2 & n \text{ par} \\ n+1 & n \text{ impar} \end{cases}$ ($n \in \mathbb{N}$)
- **Inyectividad:** Evaluamos algunos valores: $f(1) = 1+1=2$ y $f(4) = 4/2=2$. Como $f(1)=f(4)$ pero $1 \neq 4$, **no es inyectiva**.
- **Sobreyectividad:** Sea $k \in \mathbb{N}$. Queremos ver si existe $n \in \mathbb{N}$ tal que $f(n)=k$. Si tomamos $n=2k$ (que es par), entonces $f(n) = (2k)/2 = k$. Como esto vale para cualquier $k \in \mathbb{N}$, **es sobreyectiva**.
- **Biyectividad:** **No es biyectiva**.

### v) $f(a,b)=3a-2b$ ($a,b \in \mathbb{Z}$)
- **Inyectividad:** $f(2, 3) = 3(2)-2(3) = 0$ y $f(0, 0) = 3(0)-2(0) = 0$. Como $(2,3) \neq (0,0)$, **no es inyectiva**.
- **Sobreyectividad:** Sea $k \in \mathbb{Z}$. Buscamos $a,b \in \mathbb{Z}$ tales que $3a-2b=k$. Como el máximo común divisor entre 3 y 2 es 1, existen $x,y \in \mathbb{Z}$ tales que $3x-2y=1$ (identidad de Bézout, por ejemplo $x=1, y=1$). Multiplicando por $k$: $3(xk) - 2(yk) = k$. Tomando $a=xk$ y $b=yk$, tenemos $f(a,b)=k$. **Es sobreyectiva**.
- **Biyectividad:** **No es biyectiva**.

### vi) $f(a)=\begin{cases}2a& a>0\\ 1-2a& a\le0\end{cases}$ ($a \in \mathbb{Z}, f(a) \in \mathbb{N}$)
- **Inyectividad:** 
  - Si $a>0$, $f(a)$ es un número par positivo ($2, 4, 6, \dots$).
  - Si $a \le 0$, $f(a)$ es un número impar positivo ($1, 3, 5, \dots$ ya que $a=0 \to 1, a=-1 \to 3$, etc.).
  - Un número par no puede ser igual a uno impar, por lo que no hay cruces entre ramas. Dentro de cada rama, las funciones lineales son inyectivas. Por lo tanto, **es inyectiva**.
- **Sobreyectividad:** 
  - Los números pares $\{2, 4, 6, \dots\}$ son alcanzados por la rama $a>0$ (tomando $a = k/2$).
  - Los números impares $\{1, 3, 5, \dots\}$ son alcanzados por la rama $a \le 0$ (tomando $a = (1-k)/2$).
  - Como cubrimos todos los naturales, **es sobreyectiva**.
- **Biyectividad:** Como es inyectiva y sobreyectiva, **es biyectiva**.

## Bibliografía
- {puddu2012conjuntos}
- {uba2017fasciculo9}
