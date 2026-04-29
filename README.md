# Machine Learning y Deep Learning 🧠💻

**Instituto Tecnológico de Durango** **Carrera:** Ingeniería en Sistemas Computacionales  
**Facilitador:** Dr. José Gabriel Rodríguez Rivas  
**Estudiante:** Cristopher Joshua Reyes Gutiérrez  

---

## 📋 Descripción del Repositorio
Este repositorio constituye un portafolio técnico y académico que documenta la implementación de arquitecturas de aprendizaje supervisado. El contenido abarca desde la ingeniería de características y preprocesamiento avanzado hasta el despliegue de modelos de vanguardia para la resolución de problemas de regresión multivariable y clasificación binaria, con un énfasis particular en la robustez estadística, el manejo de datos desequilibrados y la generalización de modelos.

---

## 📂 Contenido del Repositorio

### 📘 Unidad 1: Preprocesamiento y Calidad de Datos
En esta unidad se sientan las bases de la integridad de los datos, aplicando protocolos rigurosos de limpieza para garantizar la fiabilidad del entrenamiento (*Data Governance*).

| Práctica | Título | Descripción | Estado |
| :---: | :--- | :--- | :---: |
| **01** | **Data Wrangling** | Implementación de flujos de limpieza, imputación estadística de nulos, estandarización y normalización de variables para la preparación de DataSheets profesionales. | ✅ |

---

### 📘 Unidad 2: Aprendizaje Supervisado (Modelado de Regresión)
Desarrollo de modelos predictivos aplicados al análisis del mercado automotriz, explorando la transición de modelos paramétricos lineales a algoritmos de ensamble de alta complejidad.

| Práctica | Título | Descripción | Estado |
| :---: | :--- | :--- | :---: |
| **01** | **Regresión Lineal Simple** | Modelado de la relación fundamental entre eficiencia y valor mediante la optimización de Mínimos Cuadrados Ordinarios. | ✅ |
| **02** | **Regresión Lineal Múltiple** | Construcción de hiperplanos de predicción multivariados para la captura de varianza compleja y reducción del sesgo estructural. | ✅ |
| **03** | **Árboles de Regresión** | Implementación de modelos no paramétricos basados en segmentación jerárquica, logrando un ajuste de alta fidelidad ($R^2 = 0.92$). | ✅ |
| **04** | **Random Forest** | Aplicación de técnicas de ensamble (*Bagging*) para la reducción de varianza y optimización de la capacidad de generalización. | ✅ |
| **05** | **SVR (Support Vector Regression)** | Optimización de márgenes de tolerancia y uso de kernels RBF para el modelado robusto en espacios de alta dimensión. | ✅ |
| **06** | **XGBoost Regressor** | Implementación de aprendizaje secuencial y boosting de gradiente para alcanzar la frontera del rendimiento predictivo. | ✅ |

---

### 📘 Unidad 3: Aprendizaje Supervisado (Métodos de Clasificación)
Fase avanzada de modelado orientada a la categorización binaria de riesgo crediticio utilizando el ecosistema de datos de **Lending Club**. Se exploran arquitecturas para solventar el desequilibrio de clases y maximizar la protección del capital institucional.

| Práctica | Título | Descripción | Estado |
| :---: | :--- | :--- | :---: |
| **01** | **KNN (Clasificación de Frutas)** | Introducción a K-Nearest Neighbors para clasificación multiclase. Análisis de métricas globales, optimización iterativa del hiperparámetro `k` y extracción de la importancia de características mediante *Permutation Importance*. | ✅ |
| **02** | **Regresión Logística** | Clasificación probabilística aplicada a riesgo financiero. Incluye ajuste de umbrales de decisión (thresholds) para optimizar la detección de impagos. | ✅ |
| **03** | **KNN (K-Nearest Neighbors)** | Clasificación basada en instancias y memoria. Se analiza el impacto crítico de la normalización de datos con `StandardScaler` en el cálculo de distancias euclidianas. | ✅ |
| **04** | **Árboles de Decisión** | Implementación de clasificadores jerárquicos con enfoque en interpretabilidad. Optimización mediante `GridSearchCV` y control de sobreajuste mediante poda (*max-depth*). | ✅ |
| **05** | **Random Forest** | Uso de clasificadores de bosque aleatorio para reducir la varianza. Se prioriza la métrica de *Recall* en la clase minoritaria para detectar eficazmente créditos no pagados. | ✅ |
| **06** | **SVM (Support Vector Machines)** | Modelado de hiperplanos óptimos que maximizan el margen entre clases. Aplicación de kernels RBF y optimización del F2-score para penalizar falsos negativos. | ✅ |
| 🏆 | **Proyecto Integrador: Titanic** | **Análisis Comparativo de Clasificadores:** Estudio exhaustivo de 5 algoritmos (LR, KNN, DT, RF, SVM) para predecir supervivencia. Incluye evaluación mediante Curvas ROC-AUC y una reflexión sociodemográfica sobre los patrones de extracción de IA. | ✅ |

---

## 📂 Estructura del Proyecto Final (Unidad III)

Para este proyecto integrador, se implementó un flujo de trabajo de Ciencia de Datos (*Pipeline*) dividido en las siguientes fases técnicas:

1. **Ingeniería de Características y EDA:** Análisis de supervivencia segmentado por género, clase socioeconómica y edad, identificando los vectores de influencia histórica.
2. **Preprocesamiento Avanzado:** Imputación estadística de valores nulos, codificación binaria de variables categóricas y estandarización paramétrica para algoritmos de base geométrica.
3. **Modelado Multiclasificador:** Entrenamiento y evaluación de cinco paradigmas de aprendizaje supervisado.
4. **Optimización de Hiperparámetros:** Búsqueda en malla (*GridSearchCV*) para la maximización del rendimiento en modelos paramétricos.
5. **Evaluación Comparativa:** Consolidación de métricas (Accuracy, Precision, Recall, F1-Score) y trazado unificado de Curvas ROC para determinar la robustez del área bajo la curva (AUC).

---

### 🚀 Casos de Aplicación en Ingeniería
Implementación de soluciones de Inteligencia Artificial para la resolución de problemáticas en infraestructuras críticas.

| Ejercicio | Título | Descripción | Estado |
| :---: | :--- | :--- | :---: |
| **Aplicación 01** | **Demanda Eléctrica** | Pronóstico de carga máxima (MW) en subestaciones eléctricas mediante Random Forest, orientado a la gestión preventiva de la red. | ✅ |

---

## 🛠️ Tecnologías y Herramientas
* **Lenguaje Principal:** Python 🐍
* **Entorno de Desarrollo:** Google Colab (Cloud Computing)
* **Stack Analítico:** Pandas (Dataframes), NumPy (Álgebra Lineal)
* **Modelado y ML:** Scikit-learn, XGBoost
* **Visualización Técnica:** Matplotlib, Seaborn, Plotly (Radar Plots, ROC-AUC Curves, Feature Importance)

---
*Repositorio actualizado automáticamente con fines académicos.*
