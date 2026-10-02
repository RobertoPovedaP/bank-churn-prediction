# 🏦 Análisis Predictivo y Modelado de Churn Bancario (Machine Learning)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Contexto del Negocio
En el sector financiero, retener a un cliente es significativamente más rentable que adquirir uno nuevo. Este proyecto tuvo como objetivo predecir la probabilidad matemática de abandono o fuga de clientes (Churn), aislando factores determinantes como la liquidez crediticia y el entorno económico para optimizar los esfuerzos de retención.

## ⚙️ Procesamiento de Datos y Metodología
Se procesó un dataset masivo de **41,388 registros y 21 variables** demográficas y macroeconómicas.
* **Prevención de Sesgo:** Limpieza rigurosa eliminando el 100% de los datos causantes de data leakage.
* **Corrección de Desbalance (SMOTE):** Se detectó un desbalance crítico en la variable objetivo (88.7% de retención vs. 11.3% de churn). Se aplicaron técnicas de ingeniería de características y remuestreo sintético (SMOTE) para neutralizar este efecto e incrementar la sensibilidad algorítmica.
* **Modelado:** Entrenamiento de algoritmos de clasificación en Python mediante Scikit-Learn.

## 💡 Impacto de Negocio
Los hallazgos técnicos se tradujeron en una estrategia de segmentación accionable:
* Proyección de optimización directa en la asignación de recursos.
* Reducción significativa en los costos operativos de telemarketing al focalizar los esfuerzos exclusivamente en el segmento del **11.3% con mayor propensión de conversión**.

## 📂 Estructura de este Repositorio
- `/data`: Muestra del dataset y diccionario de variables.
- `/notebooks`: Notebooks de Jupyter con el EDA, aplicación de SMOTE y entrenamiento de los modelos predictivos.
- `/docs`: Documentación ejecutiva del proyecto y hallazgos.