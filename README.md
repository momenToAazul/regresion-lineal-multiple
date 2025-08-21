# Regresión Lineal Múltiple - Datos NASA

## Descripción
Este repositorio contiene un análisis de **regresión lineal múltiple** aplicado a un conjunto de datos de la NASA, el cual incluye mediciones relacionadas con el comportamiento aerodinámico de distintos perfiles de alas. El objetivo principal es predecir la variable `presión sonora` a partir de cinco variables independientes: `frecuencia`, `ángulo de ataque`, `longitud`, `velocidad` y `espesor`.

Se desarrolla un flujo de trabajo completo que abarca desde la división en conjuntos de entrenamiento y validación, hasta la evaluación del modelo con métricas de desempeño y la interpretación de los coeficientes estimados.

## **Contenido del proyecto**

- Importación y exploración de la base de datos NASA (1,052 observaciones con 6 variables).
- División de los datos en conjuntos de entrenamiento (70%) y validación (30%).
- Entrenamiento de un modelo de **regresión lineal múltiple** utilizando la librería `statsmodels`.
- Análisis del modelo:
  - Resumen de resultados: coeficientes, errores estándar, estadísticos t y p-values.
  - Evaluación de significancia estadística de cada predictor.
  - Discusión sobre el coeficiente de determinación $R^2$ y el error estándar residual (RSE).
- Validación del modelo en el conjunto de prueba:
  - Cálculo manual de métricas de desempeño ($R^2$, RSE).
  - Comparación de resultados entre entrenamiento y validación.
  - Visualización de valores reales vs. estimados.
- Discusión final sobre la capacidad predictiva y las limitaciones del modelo.

## **Documentos**

- [Reporte en formato .ipynb](./RLM.ipynb)  
- [Reporte en formato .html](./RLM.html)  
- [Reporte en formato .pdf](./RLM.pdf)  
- [Base de datos .csv](./A1.3_NASA.csv)  
