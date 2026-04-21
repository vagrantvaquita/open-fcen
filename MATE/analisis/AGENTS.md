# Agents.md

## Guia de estilo

### El Hilo de Pensamiento (Heurística)

Toda resolución debe seguir un ciclo de tres etapas que refleje el proceso mental del resolutor:

1. **Encuadre e Intuición (La Hipótesis)**: Antes de operar, se debe "mirar" el objeto matemático. Se declara una sospecha o un norte basado en la forma del problema (ej: comparación de órdenes de magnitud, comportamiento asintótico). Se escribe en lenguaje natural para orientar al lector.
2. **Construcción del Camino (La Estrategia)**: Se justifica la elección de la herramienta. "Para probar X, buscaremos Y" o "Transladaremos el problema a Z para simplificar la estructura". No se salta a la cuenta sin explicar la intención.
3. **Ejecución y Refinamiento**: El desarrollo formal donde la intuición se valida con rigor.

### Ritmo y Prosodia (El Lenguaje)

El tono es el de un **Ayudante de Cátedra**: culto, preciso, pedagógico y nunca mecánico.

- **Voz Narrativa**: Se utiliza la primera persona del plural ("Observamos", "Queremos ver", "Llegamos a") para invitar al estudiante a participar del razonamiento.
- **Conectores Lógicos**: Se deben usar conectores explícitos que marquen la causalidad: *"Dado que...", "Lo que implica...", "Por otro lado...", "En virtud de..."*.
- **La Explicación del "Por Qué"**: Cada paso crítico (una sustitución, un agregado de un cero gordo, una acotación) debe estar precedido o seguido por su razón de ser.

### Arquitectura Visual y Simbólica (El Código)

La estética del desarrollo es parte del rigor.

- **Transparencia Operatoria**: Se deben mostrar las simplificaciones y cancelaciones. El uso de `\cancel` es preferido para que el lector vea qué términos "mueren" en el proceso.
- **Jerarquía de Expresiones**: Las fórmulas clave o los pasos intermedios importantes deben ir en bloques resaltados (formato bloque de KaTeX), no enterrados en el texto.
- **Cuidado Simbólico**: La notación debe ser impecable. Los conjuntos, dominios y entornos deben definirse con precisión matemática estándar.

### Finalidad y Clausura

Una resolución no termina cuando se halla el valor, sino cuando se cierra el argumento.

- **Sintetización**: Se debe volver a la pregunta original y responderla explícitamente (ej: "En conclusión, el conjunto de puntos donde se cumple X es...").
- **El Sello de Verificación**: Toda demostración o ejercicio resuelto debe finalizar con el símbolo `$\square$` seguido de una sentencia de cierre formal (ej: "$\square$ Queda así demostrada la propiedad analizada").
