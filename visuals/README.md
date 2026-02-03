# 📈 Visualizaciones: Análisis de Retención y Churn

Esta carpeta contiene las representaciones gráficas de los hallazgos clave obtenidos durante el análisis predictivo de deserción de clientes.

## 📊 Descripción Técnica: Churn por Tipo de Contrato
El gráfico principal (`churn_analysis_chart.png`) presenta la relación directa entre la estabilidad del contrato y la fuga de clientes:

* **Contratos Mes a Mes:** Muestran la tasa de deserción más alta. Son el segmento de mayor riesgo donde se concentra la pérdida de ingresos inmediatos.
* **Contratos a Largo Plazo (1-2 años):** Reflejan una tasa de lealtad significativamente mayor, validando que la estrategia de retención debe enfocarse en migrar a los clientes hacia estos modelos.

## 💡 Hallazgos Clave para el Negocio
A través de las visualizaciones, se identificaron los siguientes "puntos de dolor":
1. **Saturación de Soporte:** Los clientes con más de 4 tickets técnicos tienen una tendencia crítica al abandono.
2. **Barrera de Antigüedad:** Los primeros 6 meses son el periodo de mayor riesgo; superar esta barrera aumenta la probabilidad de retención a largo plazo en un 60%.

## 🛠️ Especificaciones
* **Herramientas:** Generado con `Seaborn` y `Matplotlib` en Python.
* **Formato:** PNG de alta resolución para reportes ejecutivos.
