# Satisfacción de Clientes de Aerolíneas

Proyecto de análisis de datos y Machine Learning enfocado en identificar los factores que influyen en la satisfacción de los clientes de una aerolínea.

A partir de un conjunto de datos con más de 129.000 registros, se realizó un proceso de limpieza, análisis exploratorio de datos (EDA), preprocesamiento de variables y entrenamiento de modelos de clasificación para predecir si un cliente se encontrará satisfecho o insatisfecho con el servicio.

Durante el proyecto se utilizaron herramientas del ecosistema de ciencia de datos en Python, incluyendo Pandas, NumPy, Matplotlib, Seaborn y Scikit-Learn.

Este trabajo fue desarrollado como proyecto académico grupal para la materia **Fundamentos de Ciencias de Datos** de la **Universidad de Palermo (UP)**.

## Dataset Utilizado
[Invistico_Airline.csv](./Invistico_Airline.csv)

## Modelos Evaluados

- Support Vector Machine (SVM)
- Regresión Logística
- Árbol de Decisión

## Resultados

| Modelo | Accuracy | ROC-AUC |
|----------|----------|----------|
| SVM | 94.63% | 98.81% |
| Regresión Logística | 83.79% | 90.94% |
| Árbol de Decisión | 85.37% | 90.57% |

El modelo SVM obtuvo el mejor desempeño general.
