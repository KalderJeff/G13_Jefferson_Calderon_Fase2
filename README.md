# Fase 2 - Componente Práctico - Machine Learning (203008067)
**Universidad Nacional Abierta y a Distancia - UNAD**

## Descripción
Desarrollo del componente práctico de la Fase 2 del curso Machine Learning, correspondiente al ítem D. Se aplican modelos supervisados de regresión y clasificación sobre dos datasets de OpenML. El notebook incluye las correcciones realizadas tras la retroalimentación del tutor.

## Datasets utilizados
| Tipo | Dataset | ID OpenML |
|---|---|---|
| Regresión | bodyfat | 560 |
| Clasificación | diabetes | 37 |

## Contenido del notebook
- **Ejercicio 1:** Contextualización de los datasets, incluyendo análisis de data leakage en bodyfat y justificación de la reducción de registros en diabetes
- **Ejercicio 2:** Análisis exploratorio (EDA) — limpieza, visualizaciones y correlaciones (con exclusión de la variable `Density`)
- **Ejercicio 3:** Modelos de regresión — Lineal, Ridge, Lasso y Árbol de Decisión (Ridge: R² = 0.6392)
- **Ejercicio 4:** Modelos de clasificación — Regresión Logística, Árbol de Decisión, KNN y Perceptrón (mejor modelo: Regresión Logística con F1-Score = 0.6575)
- **Ejercicio 5:** Feedback a compañero con evidencia del foro
- **Conclusiones:** análisis integrador de los resultados obtenidos

## Correcciones aplicadas
- Exclusión de la variable `Density` del modelado para evitar data leakage
- Justificación detallada de la reducción del dataset diabetes de 768 a 392 registros
- Actualización de visualizaciones y métricas tras las correcciones

## Requisitos
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Cómo ejecutar
1. Clonar el repositorio
2. Abrir el archivo `.ipynb` en Jupyter Notebook, Google Colab o Visual Studio Code (con la extensión de Jupyter instalada)
3. Ejecutar las celdas en orden

## Autor
**Jefferson Alexander Calderón Tabla**  
Estudiante de Ingeniería de Sistemas y Especialización en Ciencia de Datos y Analítica  
Curso: Machine Learning (203008067) — UNAD  
Mayo 2026
