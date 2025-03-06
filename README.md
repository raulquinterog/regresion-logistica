# Regresion Logistica

README - Regresión Logística y Validación Cruzada

[Código con Texto](https://github.com/raulquinterog/regresion-logistica/blob/ca031c1aaec49b6f837b6cac818aba069ad4272c/Regresio%CC%81n_logi%CC%81stica_y_validacio%CC%81n_cruzada.ipynb)

[Datos Usados]()

[Diccionario de Datos](https://github.com/raulquinterog/regresion-logistica/blob/ca031c1aaec49b6f837b6cac818aba069ad4272c/diccionario_de_datos_ce2019.csv)

### 📌 Descripción del Proyecto

Este proyecto implementa un modelo de Regresión Logística para predecir una variable binaria basada en una base de datos de actividades económicas. Se realiza selección de características con Lasso, entrenamiento del modelo, evaluación con diferentes métricas, y visualización de la Curva ROC y AUC.

### 📂 Estructura del Código

1️⃣ Importación de datos y preprocesamiento

2️⃣ Selección de características con Lasso

3️⃣ División de datos en entrenamiento y prueba (80/20)

4️⃣ Entrenamiento de Regresión Logística

5️⃣ Evaluación del modelo con matriz de confusión

6️⃣ Visualización de la Curva ROC y cálculo de AUC

7️⃣ Interpretación de coeficientes del modelo

### 📊 Resultados Principales

✔ Selección de Características
Las 5 variables más relevantes seleccionadas por Lasso fueron:

M010A

A221A

H020A

M030A

CODIGO

### ✔ Evaluación del Modelo

📌 Matriz de Confusión con umbral 0.5:

Exactitud: 81%

Sensibilidad: 56%

Especificidad: 90%


### 📌 Curva ROC y AUC:

AUC obtenido: 0.84, lo que indica que el modelo tiene buena capacidad de discriminación.
✔ Interpretación de Coeficientes
CODIGO tiene el mayor impacto negativo (-0.0151), lo que sugiere que ciertas actividades económicas están asociadas con menores ingresos.
M010A, A221A, H020A tienen coeficientes positivos, aumentando la probabilidad de clasificar en la categoría 1 (ingresos altos).

### 📌 Conclusión
El modelo de Regresión Logística con Lasso permitió identificar las variables más importantes y logró una buena precisión en la clasificación. La actividad económica (CODIGO) es un factor determinante, indicando que ciertos sectores tienen menor probabilidad de altos ingresos. 🚀

