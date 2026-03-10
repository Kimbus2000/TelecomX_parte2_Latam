# 📡 Telecom X – Predicción de Cancelación (Churn)

¡Hola! Soy Kimberly. Este proyecto es la segunda parte del desafío de Telecom X, donde paso del análisis exploratorio al desarrollo de **modelos predictivos de Machine Learning**.

## 🎯 Objetivo del Proyecto
Desarrollar un pipeline robusto capaz de prever qué clientes tienen mayor probabilidad de cancelar sus servicios, permitiendo a la empresa anticiparse con estrategias de retención.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Entorno:** Google Colab

## 📊 Pasos del Desafío
1. **Preprocesamiento:** Limpieza de datos, tratamiento de variables anidadas (JSON) y eliminación de identificadores irrelevantes.
2. **Encoding & Escalamiento:** Aplicación de One-Hot Encoding y normalización con `MinMaxScaler`.
3. **Modelado:** Entrenamiento de **Regresión Logística** y **Random Forest**.
4. **Evaluación:** Análisis de métricas (Accuracy, Precision, Recall y F1-Score) y Matrices de Confusión.

## 💡 Principales Insights
* **El contrato es clave:** Los clientes con contrato "Mes a Mes" representan el mayor riesgo de fuga.
* **Fibra Óptica:** Este segmento de red tiene una tasa de cancelación superior al promedio, sugiriendo una oportunidad de mejora en el servicio o precio.
* **Retención Temprana:** Los primeros 12 meses de antigüedad son críticos; si el cliente supera el año, la probabilidad de Churn disminuye drásticamente.

## 🏆 Conclusión
El modelo de **Regresión Logística** resultó ser el más efectivo para este negocio debido a su alto **Recall**, permitiéndonos identificar correctamente a los clientes que realmente planean irse para actuar a tiempo.

---
*Proyecto desarrollado como parte de mi formación en Data Science.*
