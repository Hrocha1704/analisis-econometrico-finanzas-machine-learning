# Análisis de Finanzas, Econometría y Machine Learning

Este repositorio contiene un análisis integral que combina técnicas de **optimización financiera**, **estadística descriptiva regional** y modelos de **Machine Learning** aplicados a datos socioeconómicos de Argentina.

## 🚀 Contenido del Proyecto

El análisis se divide en tres pilares fundamentales:

### 1. Optimización de Portafolios (Modelo Markowitz)
Se realiza un análisis de activos financieros utilizando librerías como `yfinance` y `scipy.optimize`.
* **Selección de Activos:** Basada en la correlación con Microsoft (MSFT).
* **Objetivo:** Maximización del **Ratio de Sharpe**.
* **Resultados:** Generación de pesos óptimos para una cartera diversificada (AAPL, V, HD, NKE, CSCO).

### 2. Análisis Estadístico EPH (Indec)
Procesamiento de la Encuesta Permanente de Hogares (EPH) para el segundo trimestre de 2024.
* **Cálculo de Tasas:** Estimación de la Población Económicamente Activa (PEA) y tasas de desocupación.
* **Comparativa Regional:** * **GBA:** 8.31% de desocupación.
    * **Región Pampeana:** 7.64% de desocupación.
    * **Región Cuyo:** 5.12% de desocupación.

### 3. Machine Learning: Predicción de Cobertura de Salud
Desarrollo de un modelo predictivo para identificar si un individuo posee cobertura de salud (prepaga/obra social) basándose en variables demográficas.
* **Modelo:** Árbol de Decisión (`DecisionTreeClassifier`).
* **Variables:** Edad, Género, Nivel Educativo, Estado Civil y Estado Ocupacional.
* **Performance:** Precisión general del **70.52%**.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.12
* **Librerías Principales:** * `Pandas` & `Numpy` (Manipulación de datos)
    * `Scikit-Learn` (Modelado predictivo)
    * `Statsmodels` & `Scipy` (Cálculos estadísticos y optimización)
    * `Matplotlib` (Visualización)

---
Procesado por **Hrocha1704**
