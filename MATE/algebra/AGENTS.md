# Agents.md

## Programa de la materia

El programa de la materia contiene todos los conceptos que el alumno aprendera durante el transcurso del año.

### Conjuntos, relaciones y funciones

Conjuntos: definiciones, pertenencia, contenciones, operaciones (unión, intersección, diferencia). Leyes de De Morgan. Cardinal de conjuntos finitos. Tablas de verdad y relación con lógica proposicional. Igualdad de conjuntos (diagramas de Venn, tablas). Producto cartesiano. Conjunto de Partes (y su cardinal para cjtos finitos).

Relaciones: definición, su representación como grafos. Relaciones de orden y equivalencia. Clases de equivalencia. Clausura transitiva.

Funciones: Definición. Composición. Funciones inyectivas, sobreyectivas, biyectiva, inversa.

Cuantificadores: noción intuitiva.

Taller: Introducción al manejo de las computadoras del laboratorio. Introducción a lenguaje funcional: idea de que todo es una función. Haskell: Instalación y entorno de programación (grabar, cargar, etc.). Definición de funciones simples sin recursión. Tipos básicos: Integer, Bool, Char. Definición por casos. If then else. Operaciones aritméticas, evaluación de fórmulas de la aritmética. Operaciones booleanas. Evaluación de fórmulas de la lógica proposicional solo con constantes True y False. Currificación. Producto cartesiano vs. currificación. Composición de funciones. Evaluación parcial. Evaluación eager vs. Lazy.

### Números naturales e Inducción

Definición “intuitiva” de los números naturales, primeras demostraciones por inducción (simple). Sumatoria, productoria y su escritura como ciclos en un programa. Factorial y su interpretación combinatoria (biyecciones en conjuntos finitos). Número combinatorio y su interpretación combinatoria (subconjuntos en un conjunto finito), escritura como suma de dos combinatorios, definición recursiva del combinatorio. Definición de funciones recursivas en pseudocódigo (o código en algún lenguaje concreto). Definición por los axiomas de Peano de los números naturales. Ejemplos de demostración por inducción global. Ejemplos de algoritmos recursivos (sort, Hanoi, Fibonacci) y análisis de complejidad. Cálculo de a^n por distintos algoritmos (introducción intuitiva de noción de complejidad). Inducción global y principio de buena ordenación.

Taller: Recursión. Sumatoria y productoria con y sin filtros (por ejemplo, la suma de todos los naturales <= n que cumplan con el predicado P). Definición recursiva de factorial, números combinatorios, etc. Tipos algebraicos en Haskell. Pattern matching. Tipo algebraico 1: Naturales como cero y sucesor. Definición de la suma, producto, etc. Tipo algebraico 2: Listas. Recorrido de listas. Búsqueda de un elemento, palíndromo, reverso, etc. Búsqueda de patrones en listas. Lista de listas. Tipo algebraicos 3: fórmula de la lógica proposicional. Programación de satisfacibilidad y validez. Introducción temprana de P y NP. Sorting de listas. Fibonacci: algoritmo directo (ineficiente) y con programación dinámica (eficiente). Tipo algebraico 4: Árboles binarios. Recorrido sobre árboles binarios: BFS, DFS.

### Números enteros

Enteros. Divisibilidad y primeras propiedades. Primos y Compuestos. Algoritmo de división. Aplicaciones del algoritmo de división. Escrituras en distintas bases, sistemas de numeración. Máximo común divisor. Algoritmo de Euclides (y su complejidad), escritura del máximo común divisor como combinación lineal. Numeros coprimos. Propiedades. Teorema Fundamental de la aritmética. Cantidad de primos. Criba. Aplicaciones del TFA (cantidad de divisores, cálculo de gcd y del mcm). Curiosidades de los primos. Congruencias, propiedades y aplicaciones (criterios de divisibilidad). Restos modulo m. Grupos y Anillos (comparación de Z/mZ con Z). Ecuaciones lineales diofánticas y ecuaciones de congruencia. Algoritmos. Sistemas de ecuaciones de congruencia. Teorema Chino del Resto. Pequeño Teorema de Fermat. Algoritmos probabilisticos de primalidad. de Euler-Fermat. Aplicación: Algoritmo criptográfico RSA.

Taller: Algoritmo de División. Programación (funcional) del algoritmo de Euclides y cálculo de su complejidad. Descomposición en factores primos (calcular lista de divisores). Criba de Eratóstenes. Programación de criterios de divisibilidad con enteros representados como listas de dígitos decimales. Programación de resolución de ecuaciones diofánticas lineales. Programación del teorema Chino del Resto: resolución de sistemas de congruencias. Números pseudo aleatorios. Programación de algoritmos probabilísticos de primalidad u otros algoritmos probabilísticos. Logaritmo discreto.

### Polinomios con coeficientes en un cuerpo

Cuerpos. Definición y ejemplos, Q, R, C, Z/pZ. Anillo de polinomios K[x]: generalidades (suma, producto, unidades), grado, divisibilidad, irreducibles y compuestos, algoritmo de división. Paralelismo con Z: Máximo común divisor, algoritmo de Euclides, coprimos. Factorización única.

Aspecto funcional: Evaluacion de polinomios (def y algoritmos). Raíces. Teorema del resto. Resolución de cuadraticas en K[X]. Multiplicidad. Equivalencias. Cota para el número de raíces con multiplicidad sobre un cuerpo.

C[X]: Repaso del cuerpo C, coordenadas polares, fórmulas de Moivre. Raíces/factorizacion de X^n – z en C[x]. Grupo de raíces de la unidad. Teorema Fundamental del Algebra, irreducibles de C[X].  

R[X]: Raíces complejas no reales de polinomios reales. Factorización en R[X].

Q[X]: Teorema de Gauss para calcular raíces racionales.

Ejemplos de factorización en K[X] para distintos K. Criterios de irreducibilidad sobre Q y algoritmos de factorización sobre los distintos cuerpos

Taller: Tipo algebraico 5: complejo. Programación de operaciones básicas. Representación de polinomios. Operaciones básicas con las diferentes representaciones. Complejidad de tiempo y espacio de cada una. Ejemplos de programación imperativa. Algoritmos para encontrar raíces en polinomios. Algoritmo ingenuo de factorización sobre Q. Más ejemplos de programación imperativa.

## Bibliografia

La bibliografia se encuentra en formato CSL yaml.

```{yaml}
references:

- id: denapo2020enteros
type: manuscript
title: "Aritmética de los Números Enteros (Álgebra I)"
author:
    - family: De Nápoli
      given: Pablo L.
publisher: Universidad de Buenos Aires, Departamento de Matemática
URL: 'http://mate.dm.uba.ar/~pdenapo/apuntes-algebraI/enteros.pdf'
issued:
    year: 2020
language: es

- id: uba2017fasciculo9
type: book
title: "Cursos de grado: Álgebra I (Fascículo 9)"
author:
    - literal: "Departamento de Matemática, FCEyN, Universidad de Buenos Aires"
publisher: "Universidad de Buenos Aires"
edition: "Revisión 2017"
URL: 'https://cms.dm.uba.ar/depto/public/grado/fascgrado9.pdf'
issued:
    year: 2017
language: es
note: "Comité Editorial: Carlos Cabrelli (Dir.), Gabriela Jerónimo, Claudia Lederman y Leandro Vendramin."

- id: gentileNotas
type: book
title: "Notas de Algebra"
author:
    - family: Gentile
      given: Enzo R.
publisher: EUDEBA
language: es

- id: gentile1977estructuras
type: book
title: "Estructuras algebraicas I"
author:
    - family: Gentile
      given: Enzo R.
publisher: "Organización de los Estados Americanos (OEA)"
collection-title: "Monografía científica"
issued:
    year: 1977
language: es

- id: gentile1985aritmetica
type: book
title: "Aritmética Elemental"
author:
    - family: Gentile
      given: Enzo R.
publisher: "Organización de los Estados Americanos (OEA)"
collection-title: "Monografía científica"
issued:
    year: 1985
language: es

- id: birkhoff1970algebra
type: book
title: "Algebra moderna"
author:
    - family: Birkhoff
    given: Garrett
    - family: Mac Lane
      given: Saunders
publisher: Vicens-Vives
edition: 4
issued:
    year: 1970
language: es

- id: bird1988functional
type: book
title: "An Introduction to Functional Programming"
author:
    - family: Bird
    given: Richard S.
    - family: Wadler
      given: Philip L.
publisher: Prentice-Hall
issued:
    year: 1988

- id: bird1998haskell
type: book
title: "Introduction to Functional Programming Using Haskell"
author:
    - family: Bird
      given: Richard
publisher: Prentice-Hall
issued:
    year: 1998

- id: dijkstra1997discipline
type: book
title: "A Discipline of Programming"
author:
    - family: Dijkstra
      given: Edsger
publisher: Prentice Hall
issued:
    year: 1997

- id: puddu2012conjuntos
type: manuscript
title: "Conjuntos, relaciones y funciones"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Conjuntos-Puddu.pdf'
issued:
    year: 2012

- id: puddu2012naturales
type: manuscript
title: "Números naturales, principio de inducción"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Naturales-Puddu.pdf'
issued:
    year: 2012

- id: puddu2012combinatoria
type: manuscript
title: "Combinatoria"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Combinatoria-Puddu.pdf'
issued:
    year: 2012

- id: puddu2012enteros
type: manuscript
title: "Números enteros"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Enteros-Puddu.pdf'
issued:
    year: 2012

- id: krick2011enteros
type: manuscript
title: "Números enteros"
author:
    - family: Krick
      given: Teresa
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/enteros2011-4.pdf'
issued:
    year: 2011

- id: puddu2012complejos
type: manuscript
title: "Números complejos"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Complejos-Puddu.pdf'
issued:
    year: 2012

- id: puddu2012polinomios
type: manuscript
title: "Polinomios"
author:
    - family: Puddu
      given: Susana
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/1ercuat2012/algebra_I/Polinomios-Puddu.pdf'
issued:
    year: 2012

- id: pacettiGrana2012notas
type: manuscript
title: "Notas de Algebra I"
author:
    - family: Pacetti
      given: Ariel
    - family: Graña
      given: Matías
publisher: "Universidad de Buenos Aires, Departamento de Matemática"
URL: 'http://cms.dm.uba.ar/academico/materias/2docuat2012/algebra_I/main.pdf'
issued:
    year: 2012
```
