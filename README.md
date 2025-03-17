# Clasificación de Enfermedades Cardíacas

## Descripción

Este proyecto tiene como objetivo predecir si un paciente tiene o no una enfermedad cardíaca utilizando **Machine Learning**. Se implementó un modelo de **Regresión Logística**, optimizado con **GridSearchCV**, y se evaluó su desempeño utilizando validación cruzada y diversas métricas de clasificación.

## Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib & Seaborn
- Jupyter Notebook

## Resultados

El modelo obtuvo los siguientes desempeños promedio en validación cruzada:

- **Accuracy:** 84.8%
- **Precisión:** 82.16%
- **Recall:** 92.73%
- **F1-score:** 87.05%

La matriz de confusión mostró:

- **3 falsos negativos** (pacientes enfermos mal clasificados como sanos).
- **4 falsos positivos** (pacientes sanos mal clasificados como enfermos).

## Evaluación

El objetivo inicial era alcanzar un **95% de precisión**. Aunque el modelo tuvo buenos resultados, no logró superar esta meta. Esto indica que aún hay margen de mejora.

## Posibles Mejoras

- **Probar otros modelos como CatBoost o XGBoost.
- **Optimizar hiperparámetros** con una búsqueda más exhaustiva.
- **Recolección de más datos** para mejorar el aprendizaje del modelo.
- **Ajustar el umbral de decisión** para minimizar errores críticos.

## Conclusión

El modelo desarrollado es una herramienta prometedora para la detección de enfermedades cardíacas. A pesar de que no alcanzó el umbral de precisión deseado, con ajustes y mejoras adicionales podría lograr un mejor desempeño.

**¡Sigamos mejorándolo!**

