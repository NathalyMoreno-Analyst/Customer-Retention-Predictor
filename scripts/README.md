# 🐍 Scripts de Análisis: Predicción de Churn

Esta carpeta contiene el motor lógico desarrollado en Python para el análisis preventivo de deserción.

## 🛠️ Especificaciones Técnicas
El notebook `Customer_Churn_Predictor.ipynb` ejecuta las siguientes fases:

1. **Ingeniería de Características:** Transformación de variables categóricas para el análisis de riesgo.
2. **Algoritmo de Scoring:** Cálculo de probabilidad de fuga basado en correlaciones históricas.
3. **Automatización de Salida:** El script genera el archivo `Accionable_Retencion_Clientes.xlsx`, una herramienta lista para el equipo de Customer Success.

## 📦 Librerías Principales
* **Pandas:** Manipulación y limpieza de datos.
* **Matplotlib & Seaborn:** Visualización de patrones de comportamiento.
* **Plotly:** Análisis exploratorio interactivo.

---
*Código diseñado para ser escalable e integrable con bases de datos SQL o archivos CSV de plataformas CRM.*
