Probar identidades entre conjuntos requiere, en general, demostrar la igualdad de las funciones características o utilizar las leyes del álgebra de conjuntos, como las Leyes de De Morgan y la distributividad. 

Para demostrar que $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$, observamos que la intersección es distributiva respecto a la diferencia simétrica. Desarrollando el lado izquierdo tenemos $A \cap (B \triangle C) = A \cap ((B \cap C^c) \cup (C \cap B^c)) = (A \cap B \cap C^c) \cup (A \cap C \cap B^c)$. Por otro lado, expandiendo el lado derecho obtenemos $(A \cap B) \triangle (A \cap C) = ((A \cap B) - (A \cap C)) \cup ((A \cap C) - (A \cap B)) = ((A \cap B) \cap (A^c \cup C^c)) \cup ((A \cap C) \cap (A^c \cup B^c))$. Al distribuir la intersección, los términos con $A \cap A^c$ se anulan por ser el conjunto vacío, quedando $(A \cap B \cap C^c) \cup (A \cap C \cap B^c)$, lo que prueba la igualdad.

Para la identidad $A - (B - C) = (A - B) \cup (A \cap C)$, utilizamos la definición de diferencia: $A - (B - C) = A \cap (B \cap C^c)^c$. Aplicando la ley de De Morgan, esto es $A \cap (B^c \cup C)$, y por distributividad obtenemos $(A \cap B^c) \cup (A \cap C)$, que equivale a $(A - B) \cup (A \cap C)$.

En el caso de la inclusión $A \triangle B \subseteq (A \triangle C) \cup (B \triangle C)$, sea $x \in A \triangle B$. Esto significa que $x$ pertenece a $A$ o a $B$, pero no a ambos. Si $x \in A$ y $x \notin B$, consideramos la pertenencia a $C$: si $x \in C$, entonces $x \in C$ y $x \notin B$, por lo que $x \in B \triangle C$; si $x \notin C$, entonces $x \in A$ y $x \notin C$, por lo que $x \in A \triangle C$. El razonamiento es análogo si $x \in B$ y $x \notin A$, concluyendo en cualquier caso que $x$ pertenece a la unión de las diferencias simétricas con $C$.

Para probar $(A \cap C) - B = (A - B) \cap C$, aplicamos la definición de diferencia y las propiedades asociativa y conmutativa de la intersección: $(A \cap C) - B = (A \cap C) \cap B^c = (A \cap B^c) \cap C = (A - B) \cap C$.

Si asumimos que $A \subseteq B$, entonces $A - B = \emptyset$. La diferencia simétrica $A \triangle B = (A - B) \cup (B - A)$ se simplifica entonces a $\emptyset \cup (B - A) = B \cap A^c$.

La equivalencia $A \subseteq B \iff B^c \subseteq A^c$ es una aplicación directa de la contraposición lógica a la definición de inclusión: la afirmación de que todo elemento de $A$ está en $B$ es equivalente a decir que si un elemento no está en $B$, entonces no puede estar en $A$.

Finalmente, si $A \cap C = \emptyset$, entonces $A \cap (B \triangle C) = A \cap B$. Utilizando la propiedad distributiva demostrada al inicio, $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$. Dado que $A \cap C = \emptyset$, la expresión se reduce a $(A \cap B) \triangle \emptyset$, lo que por definición de diferencia simétrica es simplemente $A \cap B$.

Este ejercicio resalta la importancia de dominar las propiedades fundamentales del álgebra de conjuntos, las cuales permiten simplificar expresiones lógicas complejas y transformar inclusiones en igualdades bajo condiciones específicas.
