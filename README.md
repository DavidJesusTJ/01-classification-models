# Modelos de Clasificación

---

## Descripción General:

Este módulo tiene como objetivo explorar, implementar y evaluar una amplia variedad de modelos de clasificación disponibles en la literatura, tanto clásicos como modernos, utilizando un flujo de trabajo completo que va desde el Análisis Exploratorio de Datos (EDA) hasta la construcción, validación y reporte de resultados.

La intención es no solo aplicar modelos de clasificación, sino también mostrar el razonamiento estadístico y computacional detrás de cada paso, documentando las mejores prácticas y resaltando la utilidad de cada técnica en contextos reales.

---

## Finalidad del Proyecto

* Cobertura amplia de técnicas de clasificación: desde métodos estadísticos como Logistic Regression o Linear Discriminant Analysis hasta modelos más complejos como Gradient Boosting, Support Vector Machines y Neural Networks.
* Pipeline completo: partiendo de un EDA exhaustivo, seguido de la preparación y transformación de datos, selección de variables, entrenamiento de modelos, evaluación y comparación.
* Enfoque práctico y teórico: cada modelo estará acompañado de una explicación técnica, fórmulas clave, casos de uso y resultados obtenidos.
* Reproducibilidad y transparencia: todo el código y la documentación estarán organizados para que cualquier persona pueda replicar y adaptar el análisis a sus propios datos.

---

## Flujo de trabajo

1. **Carga y comprensión de los datos**
  * Inspección inicial de las variables.
  * Identificación de tipos de datos y tratamiento de valores faltantes.
  * Análisis de balance/desbalance de clases.

2. **Análisis Exploratorio de Datos (EDA)**

  * Estadísticos descriptivos.
  * Visualización de distribuciones y relaciones.
  * Identificación de patrones y posibles problemas en los datos.

3. **Preprocesamiento**

  * Codificación de variables categóricas.
  * Escalado y normalización.
  * Selección y/o generación de nuevas variables.

4. **Entrenamiento de modelos**

  * Implementación de múltiples clasificadores.
  * Ajuste de hiperparámetros mediante técnicas como Grid Search o Random Search.
  * Validación cruzada para evaluar robustez.

5. **Evaluación y comparación**

  * Métricas: Accuracy, Precision, Recall, F1-score, ROC-AUC.
  * Matriz de confusión y análisis de errores.
  * Comparación visual de desempeño entre modelos.

6. **Reporte final**

  * Resumen de hallazgos.
  * Interpretación de resultados.
  * Recomendaciones para producción o futuras mejoras.

---

## Modelos a implementar

* Modelos estadísticos:

  * Logistic Regression
  * Ridge Classifier
  * Linear Discriminant Analysis (LDA)
  * Quadratic Discriminant Analysis (QDA)
  * Naive Bayes (Gaussian, Multinomial, Bernoulli)

* Modelos basados en distancias:

  * K-Nearest Neighbors (KNN)
  * Radius Neighbors
  * Nearest Centroid

* Modelos de margen máximo:

  * Support Vector Machines (SVC, NuSVC, LinearSVC)

* Modelos de ensamble:

  * Random Forest
  * Gradient Boosting
  * XGBoost
  * LightGBM
  * CatBoost

* Modelos neuronales:

  * Multi-Layer Perceptron (MLPClassifier)
  * Modelos semi-supervisados:
  * Label Propagation
  * Label Spreading

---

## Valor agregado de este repositorio

Este repositorio no se limita a “probar modelos y mostrar métricas”, sino que busca:

* Enseñar cómo pensar y actuar como un científico de datos al trabajar con problemas de clasificación.
* Documentar casos prácticos que permitan aplicar este conocimiento en diferentes áreas (marketing, finanzas, salud, etc.).
* Servir como base de estudio para estudiantes y profesionales que deseen profundizar en Machine Learning supervisado.

---

## Estructura de la carpeta

01-classification-models/
│
├── 0_data/                # Conjuntos de datos de ejemplo.
├── 1_eda/                 # Análisis exploratorio de los datos.
├── 2_preprocessing/       # Preprocesamiento de los Datos.
├── 3_model/               # Modelado de datos donde se calculan metricas de evaluación y se realiza el tunning del modelo.
├── 4_reports/             # Reportes generados con resultados y análisis
└── README.md              # Explicación teórica del modelo
