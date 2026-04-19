---
titulo: Solución de Álgebra I - Práctica 1
ejercicio: 36
---

# Ejercicio 36

Sea $f: \{1,2,3,4\} \to \{1,2,3,4\}$ una función fija. Consideremos el conjunto $\mathcal{F}=\{g:\{1,2,3,4\}\longrightarrow\{1,2,3,4,5,6,7,8\}\}$ y la relación $\mathcal{R}$ en $\mathcal{F}$ dada por:
$$g\mathcal{R}h \iff g \circ f = h \circ f$$

## i) Probar que $\mathcal{R}$ es una relación de equivalencia

Para demostrar que $\mathcal{R}$ es una relación de equivalencia, verificamos las tres propiedades fundamentales {puddu2012conjuntos}:

*   **Reflexividad:** Para toda $g \in \mathcal{F}$, se cumple que $g \circ f = g \circ f$, por lo tanto $g\mathcal{R}g$.
*   **Simetría:** Si $g\mathcal{R}h$, entonces $g \circ f = h \circ f$. Por la propiedad de simetría de la igualdad, $h \circ f = g \circ f$, luego $h\mathcal{R}g$.
*   **Transitividad:** Si $g\mathcal{R}h$ y $h\mathcal{R}k$, entonces $g \circ f = h \circ f$ y $h \circ f = k \circ f$. Por transitividad de la igualdad, $g \circ f = k \circ f$, luego $g\mathcal{R}k$.

**¿Es siempre antisimétrica?**
No necesariamente. Para que $\mathcal{R}$ sea antisimétrica, de $g\mathcal{R}h$ y $h\mathcal{R}g$ debería seguirse que $g = h$. Sin embargo, si $f$ no es sobreyectiva, existen elementos en su codominio que no están en su imagen. Las funciones $g$ y $h$ podrían diferir en esos puntos y aun así cumplir $g \circ f = h \circ f$.
Por ejemplo, si $f(x) = 1$ para todo $x$, entonces $g\mathcal{R}h$ siempre que $g(1) = h(1)$, independientemente de lo que valgan $g$ y $h$ en 2, 3 o 4.

## ii) Clase de equivalencia si $f$ es sobreyectiva

Supongamos que $f$ es sobreyectiva. Como $f$ es una función de un conjunto finito $\{1,2,3,4\}$ en sí mismo, al ser sobreyectiva es también inyectiva y, por lo tanto, biyectiva {uba2017fasciculo9}.

Si $f$ es biyectiva, existe su inversa $f^{-1}$. Analicemos la condición de la clase de equivalencia:
$$g\mathcal{R}h \iff g \circ f = h \circ f$$
Si componemos con $f^{-1}$ a la derecha en ambos lados:
$$(g \circ f) \circ f^{-1} = (h \circ f) \circ f^{-1}$$
$$g \circ (f \circ f^{-1}) = h \circ (f \circ f^{-1})$$
$$g \circ Id = h \circ Id$$
$$g = h$$

Por lo tanto, si $f$ es sobreyectiva, cada función $g$ solo está relacionada consigo misma.
La clase de equivalencia de cada $g \in \mathcal{F}$ es el conjunto unitario:
$$[g]_{\mathcal{R}} = \{g\}$$

Este es un caso donde la relación de equivalencia coincide con la igualdad de funciones.

---
Bibliografía consultada: {puddu2012conjuntos}, {uba2017fasciculo9}.
