# Módulo 2 - Excel Skills for Business: Essentials

## Descripción general

En este módulo se profundizó en el uso de **funciones, fórmulas y referencias de celdas** aplicadas al análisis y gestión de datos en Excel.  
El enfoque estuvo en automatizar cálculos, trabajar con referencias relativas y absolutas, y vincular información entre diferentes hojas de cálculo.

---

## Temas aprendidos

1. **Funciones básicas de cálculo**
   - `=SUMA(A1:A10)` → Suma un rango de celdas.  
   - `=PROMEDIO(B2:B15)` → Calcula el promedio de valores.  
   - `=MAX(C2:C20)` / `=MIN(C2:C20)` → Obtiene el valor máximo y mínimo.  

2. **Referencias de celdas**
   - **Relativas:** se ajustan al copiar (ej. `=A1+B1`).  
   - **Absolutas:** se fijan con `$` (ej. `=$A$1+B1`).  
   - **Mixtas:** combinan elementos fijos y variables (`=$A1+B$1`).  

3. **Vinculación entre hojas**
   - Permite usar valores de otras hojas:  
     `=Hoja2!B5` o `=SUMA(Hoja1!C2:Hoja1!C10) + Hoja2!B3`.

---

## Retos prácticos

### Desafío 1: Presupuesto de viaje escolar
**Objetivo:** Calcular gastos totales (transporte, alimentación y entradas).  
**Aplicación:** uso de `SUMA`, `PROMEDIO`, `MAX`, `MIN` y referencias absolutas.  
**Resultado:** presupuesto automatizado con costo total y costo por estudiante.

### Desafío 2: Presupuesto de Greenscape Landscaping
**Objetivo:** Elaborar un presupuesto de materiales y mano de obra.  
**Aplicación:** referencias mixtas y totales automáticos.  
**Resultado:** hoja dinámica que actualiza costos al cambiar cantidades o precios.

### Desafío 3: Cálculo de nómina
**Objetivo:** Automatizar cálculos de salarios, deducciones e impuestos.  
**Aplicación:** referencias absolutas y funciones básicas.  
**Resultado:** hoja precisa con fórmulas automatizadas y errores reducidos.

---

## Práctica adicional: uso de rangos en Excel

**Objetivo:** Dominar el concepto de rangos mediante un ejercicio interactivo.  

**Actividad:**  
- **Paso 1:** Descargar y abrir el libro de ejercicios *Sopa de letras de Excel*.  
- **Paso 2:** Buscar las palabras dentro de la sopa de letras y escribir el **rango correspondiente** en la columna “Rango”.  
  Si el rango es correcto, la columna **“Correcto”** se mostrará en verde.  
  Las palabras solo se ubican **horizontal o verticalmente**, no en diagonal ni al revés.  

**Competencia reforzada:**  
Comprender la estructura y sintaxis de los rangos (adyacentes y no adyacentes), fundamentales para el uso de fórmulas y análisis de datos.

Ejemplos:
Rango adyacente: A1:C3
Rango no adyacente: A1:A2,C1:C2

---

## Atajos de teclado (Windows y Mac)

| Acción | Windows | Mac |
|--------|----------|------|
| Deshacer acción anterior | **Ctrl + Z** | **Cmd + Z** |
| Cambiar tipo de referencia (absoluta/mixta/relativa) | **F4** | **Fn + F4 / Cmd + T** |
| Mostrar fórmulas en la hoja | **Ctrl + ` (~)** | **Ctrl + ` (~)** |
| Abrir generador de funciones | **Shift + F3** | **Ctrl + A** |
| Ir a la hoja anterior | **Ctrl + RePág** | **Cmd + RePág** |
| Ir a la hoja siguiente | **Ctrl + AvPág** | **Cmd + AvPág** |

Fuentes: [Soporte de Microsoft Office (Windows)](https://support.microsoft.com/es-es/excel) | [Soporte de Microsoft Office (Mac)](https://support.microsoft.com/es-es/excel)

---

## Terminología de Excel

| Concepto | Descripción |
|-----------|-------------|
| **Fórmula** | Expresión que realiza un cálculo. Siempre inicia con `=`. Ejemplo: `=A1+B1`. |
| **Función** | “Miniprograma” que realiza cálculos complejos dentro de una fórmula. Ejemplo: `=SUMA(A1:A12)`. |
| **Barra de fórmulas** | Área ubicada bajo la cinta; muestra o edita el contenido de la celda activa. |
| **Valor** | Dato numérico usado en cálculos. El texto sin formato se considera etiqueta. |
| **Rango** | Conjunto de celdas, adyacentes o no (ej. `A1:C2` o `A1:A2,C1:C2`). |
| **Referencia relativa** | Cambia al copiar la fórmula. Ejemplo: `A2` → `A3`. |
| **Referencia absoluta** | No cambia al copiar. Se define con `$` (ej. `$A$1`). |

---

## Consejo ninja de la semana: orden de operaciones

Excel sigue las reglas matemáticas convencionales:
- **Multiplicación ( * )** y **División ( / )** tienen prioridad sobre **Suma ( + )** y **Resta ( - )**.  

Ejemplo:
=3+4*5 → resultado: 23
=(3+4)*5 → resultado: 35

Usar **paréntesis** permite definir el orden exacto de los cálculos.

---

## Conclusión

El Módulo 2 consolidó las bases de las fórmulas, referencias y rangos en Excel, aplicadas en contextos empresariales y educativos.  
El aprendizaje de funciones clave, junto con la práctica de rangos y referencias, permite desarrollar hojas de cálculo automatizadas, precisas y listas para el análisis profesional.