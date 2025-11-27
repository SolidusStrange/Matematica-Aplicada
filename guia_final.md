# Pregunta 1 — Sucesión aritmética explícita
**Enunciado:**  
Sea la sucesión:
$${a_n = 48 + 0.7n}$$
Calcule el término en la posición 34.

**Cómo abordar:**  
Es una sucesión aritmética en forma explícita: basta sustituir el valor de \(n\).

**Desarrollo:**  
1. Escribir la fórmula.  
2. Reemplazar \(n = 34\).  
3. Operar sin llegar a la respuesta final.

---

# Pregunta 2 — Ecuación cúbica
**Enunciado:**  
$${a_n = n^3 - 2n}$$  
Calcular \(n\) tal que:
$${a_n = 2171}$$

**Cómo abordar:**  
Se iguala la sucesión al valor dado y se resuelve la ecuación cúbica.

**Desarrollo:**  
1. Plantear:
   $$n^3 - 2n = 2171$$
2. Reordenar:
   $$n^3 - 2n - 2171 = 0$$
3. Probar valores enteros cercanos a la raíz cúbica.

---

# Pregunta 3 — Sucesión aritmética aplicada
**Enunciado:**  
Una aplicación recibe actualizaciones semanales. La primera pesa 200 MB y cada semana aumenta 50 MB.

**Cómo abordar:**  
El aumento es constante → sucesión aritmética.

**Fórmula:**  
$${a_n = a_1 + (n-1)d}$$

**Desarrollo:**  
1. Identificar \(a_1 = 200\).  
2. Identificar \(d = 50\).  
3. Construir la fórmula general.

---

# Pregunta 4 — Sucesión geométrica aplicada
**Enunciado:**  
Un jugador inicia con 4 fichas y duplica cada vez que gana.

**Cómo abordar:**  
Duplicar → razón geométrica \(r = 2\).

**Fórmula:**  
$${a_n = a_1 r^{n-1}}$$

**Desarrollo:**  
1. \(a_1 = 4\).  
2. \(r = 2\).  
3. Armar la expresión general.

---

# Pregunta 5 — Fórmula explícita
**Enunciado:**  
$${a_n = 900 - (n-1)100}$$  
Calcular para \(n = 5\).

**Cómo abordar:**  
Solo sustituir el valor de \(n\).

**Desarrollo:**  
1. Reemplazar \(n = 5\).  
2. Operar.

---

# Pregunta 6 — Suma de sucesión geométrica
**Enunciado:**  
Una empresa capacita 7 trabajadores el primer mes y cada mes duplica el número. Hallar el total capacitado en 12 meses.

**Fórmulas:**  
$${a_n = a_1 r^{n-1}}$$  
$${S_n = a_1 \frac{r^n - 1}{r - 1}}$$

**Cómo abordar:**  
Se trata de una SG y piden la suma.

**Desarrollo:**  
1. \(a_1 = 7\), \(r = 2\).  
2. Sustituir en \(S_{12}\).

---

# Pregunta 7 — Orden de matriz
**Enunciado:**  
Matriz:
```
A = [[-2, 5, -1],
     [-8, 4, 0]]
```

¿Tiene orden 3 × 2?

**Cómo abordar:**  
Contar filas y columnas.

**Desarrollo:**  
1. Identificar filas: 2.  
2. Identificar columnas: 3.  
3. Comparar con el orden propuesto.

---

# Pregunta 8 — Elemento a₁₂
**Enunciado:**  
Determinar si:
$${a_{12} = 5}$$

**Cómo abordar:**  
\(a_{12}\) corresponde a fila 1, columna 2.

**Desarrollo:**  
1. Ubicar elemento en la matriz.  
2. Verificar si coincide.

---

# Pregunta 9 — Transpuesta de matriz
**Enunciado:**  
¿Es esta la transpuesta de A?
```
[[-1, 0],
 [ 5, 4],
 [-2, 8]]
```

**Cómo abordar:**  
Calcular la transpuesta de A y compararla.

**Desarrollo:**  
1. Intercambiar filas por columnas.  
2. Revisar coincidencia.

---

# Pregunta 10 — Suma de matrices
**Enunciado:**  
Matrices:
```
A = [[30, 50],
     [25, 18],
     [12, 16],
     [ 9, 40]]

B = [[10, 30],
     [15, 27],
     [24, 14],
     [10, 22]]
```

Interpretar \(c_{21}\) en \(C = A + B\).

**Cómo abordar:**  
Se suma elemento a elemento.  
Luego se interpreta fila 2, columna 1 según contexto.

**Desarrollo:**  
1. Sumar segunda fila, primera columna.  
2. Interpretar significado.

---

# Pregunta 11 — Multiplicación matricial
**Enunciado:**  
Matrices:
```
A = [[100, 200, 150],
     [250, 300, 100]]

B = [[2, 1],
     [3, 2],
     [4, 5]]
```

**Cómo abordar:**  
Cantidad × costo → multiplicación \(A \cdot B\).

**Desarrollo:**  
1. Ver dimensiones.  
2. Multiplicar filas por columnas.

---

# Pregunta 12 — Nutrientes por día
**Enunciado:**  
```
N = [[13, 17],
     [11,  5],
     [ 3,  2]]

C = [[2, 4],
     [2, 1]]

R = [[60, 69],
     [32, 49],
     [10, 14]]
```

Identificar grasas día 1.

**Cómo abordar:**  
Grasas = fila 2.  
Día 1 = columna 1.

**Desarrollo:**  
1. Ubicar fila 2.  
2. Leer columna 1.

---

# Pregunta 13 — Aumento porcentual
**Enunciado:**  
Producción abril:
```
I = [[270, 520, 430],
     [380, 290, 600],
     [150, 310, 360]]
```

Aumento del 30% en mayo.

**Cómo abordar:**  
Tomar elemento (fila, columna) solicitado y multiplicar por 1.30.

**Desarrollo:**  
1. Identificar conector 1 y planta 2.  
2. Aplicar incremento.

---

# Pregunta 14 — Sistema y forma matricial
**Enunciado:**  
Sistema:
$${900x + 1900y = 70000}$$  
$${x + y = 60}$$

Forma matricial:
```
A = [[900, 1900],
     [  1,    1]]

X = [[x],
     [y]]

B = [[70000],
     [   60]]
```

**Cómo abordar:**  
Representar en forma \(AX = B\) y resolver.

**Desarrollo:**  
1. Plantear la ecuación matricial.  
2. Resolver usando inversión o sustitución.

---

Fin del documento.
