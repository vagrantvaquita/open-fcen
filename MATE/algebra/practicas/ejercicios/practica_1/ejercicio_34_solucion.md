---
titulo: Solución de Álgebra I - Práctica 1
ejercicio: 34
---

# Ejercicio 34

Sean $A, B$ y $C$ conjuntos, y consideremos las funciones $f: B \to C$ y $g: A \to B$.

## i) Si $f \circ g$ es inyectiva, entonces $g$ es inyectiva

**Demostración:**
Queremos ver que para todo $a_{1}, a_{2} \in A$, si $g(a_{1}) = g(a_{2})$, entonces $a_{1} = a_{2}$.
Supongamos que $g(a_{1}) = g(a_{2})$. Entonces, aplicando la función $f$ a ambos lados de la igualdad:
$$f(g(a_{1})) = f(g(a_{2}))$$
$$(f \circ g)(a_{1}) = (f \circ g)(a_{2})$$
Como por hipótesis $f \circ g$ es inyectiva, de la igualdad anterior se deduce que $a_{1} = a_{2}$. Por lo tanto, $g$ es inyectiva.

## ii) Si $f \circ g$ es sobreyectiva, entonces $f$ es sobreyectiva

**Demostración:**
Queremos ver que para todo $c \in C$, existe un $b \in B$ tal que $f(b) = c$.
Sea $c \in C$. Como $f \circ g: A \to C$ es sobreyectiva por hipótesis, existe un $a \in A$ tal que $(f \circ g)(a) = c$.
Por definición de composición, esto significa que $f(g(a)) = c$.
Llamemos $b = g(a)$. Dado que $g: A \to B$, tenemos que $b \in B$. Entonces, hemos encontrado un $b \in B$ tal que $f(b) = c$. Por lo tanto, $f$ es sobreyectiva.

## iii) Si $f$ y $g$ son inyectivas, entonces $f \circ g$ es inyectiva

**Demostración:**
Sean $a_{1}, a_{2} \in A$ tales que $(f \circ g)(a_{1}) = (f \circ g)(a_{2})$.
Esto es equivalente a $f(g(a_{1})) = f(g(a_{2}))$.
Como $f$ es inyectiva por hipótesis, de la igualdad anterior se deduce que $g(a_{1}) = g(a_{2})$.
Finalmente, como $g$ también es inyectiva, concluimos que $a_{1} = a_{2}$. Por lo tanto, $f \circ g$ es inyectiva.

## iv) Si $f$ y $g$ son sobreyectivas, entonces $f \circ g$ es sobreyectiva

**Demostración:**
Sea $c \in C$. Como $f$ es sobreyectiva, existe un $b \in B$ tal que $f(b) = c$.
Para ese $b \in B$, como $g$ es sobreyectiva, existe un $a \in A$ tal que $g(a) = b$.
Sustituyendo $b$ en la primera ecuación: $f(g(a)) = c$.
Entonces, $(f \circ g)(a) = c$. Esto prueba que para todo $c \in C$ existe un $a \in A$ tal que su imagen bajo $f \circ g$ es $c$. Por lo tanto, $f \circ g$ es sobreyectiva.

## v) Si $f$ y $g$ son biyectivas, entonces $f \circ g$ es biyectiva

**Demostración:**
Una función es biyectiva si y solo si es inyectiva y sobreyectiva {puddu2012conjuntos}.
Como $f$ y $g$ son biyectivas, ambas son inyectivas. Por el inciso (iii), $f \circ g$ es inyectiva.
Como $f$ y $g$ son biyectivas, ambas son sobreyectivas. Por el inciso (iv), $f \circ g$ es sobreyectiva.
Al ser $f \circ g$ inyectiva y sobreyectiva, concluimos que $f \circ g$ es biyectiva.

---

Bibliografía consultada: {puddu2012conjuntos}, {uba2017fasciculo9}.
