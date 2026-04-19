---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 10
---

# Solución del Ejercicio 10

Dos proposiciones son equivalentes si y solo si poseen los mismos valores de verdad para todas las combinaciones posibles de sus variables proposicionales. Para verificar esto, utilizaremos tablas de verdad {puddu2012conjuntos}.

### i) $p \Rightarrow q \equiv \sim q \Rightarrow \sim p \equiv \sim p \vee q \equiv \sim (p \wedge \sim q)$

Construimos la tabla de verdad para las cuatro expresiones:

| $p$ | $q$ | $p \Rightarrow q$ | $\sim q$ | $\sim p$ | $\sim q \Rightarrow \sim p$ | $\sim p \vee q$ | $p \wedge \sim q$ | $\sim (p \wedge \sim q)$ |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| V | V | **V** | F | F | **V** | **V** | F | **V** |
| V | F | **F** | V | F | **F** | **F** | V | **F** |
| F | V | **V** | F | V | **V** | **V** | F | **V** |
| F | F | **V** | V | V | **V** | **V** | F | **V** |

Dado que las columnas en negrita coinciden en todos sus valores, concluimos que las cuatro proposiciones son equivalentes. La equivalencia $p \Rightarrow q \equiv \sim q \Rightarrow \sim p$ es la base de la **demostración por contrarrecíproco**.

### ii) $\sim (p \Rightarrow q) \equiv p \wedge \sim q$

Construimos la tabla de verdad para ambas expresiones:

| $p$ | $q$ | $p \Rightarrow q$ | $\sim (p \Rightarrow q)$ | $\sim q$ | $p \wedge \sim q$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| V | V | V | **F** | F | **F** |
| V | F | F | **V** | V | **V** |
| F | V | V | **F** | F | **F** |
| F | F | V | **F** | V | **F** |

Nuevamente, las columnas en negrita coinciden. Esta equivalencia justifica la **demostración por reducción al absurdo**: para probar que $p \Rightarrow q$ es verdadera, se supone que su negación $p \wedge \sim q$ es verdadera y se busca llegar a una contradicción {uba2017fasciculo9}.
