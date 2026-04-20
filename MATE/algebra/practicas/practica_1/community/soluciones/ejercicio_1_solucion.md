---
title: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
category: Conjuntos
description: Un ejercicio a resolver dentro de la practica.
practica: practica_1
ejercicio: ejercicio_1
---

Recordemos:

* $x \in A$: El objeto x es un elemento que está suelto adentro del conjunto $A$.
* $B \subseteq A$: Todos los elementos del conjunto $B$ también son elementos de $A$.

Analicemos cada caso para $A=\{1,2,3\}$:

$1 \in A$ es **verdadero**. El número 1 es literalmente uno de los objetos que listamos dentro del conjunto $A$.

$\{1\} \subseteq A$ es **verdadero**. Aquí $\{1\}$ es un conjunto que contiene al elemento 1. Como el 1 pertenece a $A$, entonces el conjunto que lo contiene está incluido en $A$.

$\{2,1\} \subseteq A$ es **verdadero**. Para que esto sea cierto, tanto el 2 como el 1 deben estar en $A$. Como ambos están, la inclusión es válida. (Recordá que en conjuntos el orden no importa, {2,1} es lo mismo que {1,2}).

$\{1,3\} \in A$ es **falso**. Para que esto fuera verdadero, adentro de $A$ tendría que haber un "paquete" que fuera $\{1,3\}$. Es decir, $A$ tendría que verse así: $A = \{1,2,3,\{1,3\}\}$. Pero en nuestro $A$, solo hay números, no hay conjuntos como elementos. Lo correcto sería decir $\{1,3\} \subseteq A$.

$\{2\} \in A$ es **falso**. Por la misma razón que la anterior. El número 2 pertenece a $A$ ($2 \in A$), pero el conjunto que contiene al dos no es un elemento de $A$.
