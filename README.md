# Modelo-Logistico-Para-Detecci-n-de-Cancer-de-Mama
Modelo Logistico Para Detección de Cáncer de Mama


🧪 Clasificación de Cáncer de Mama con Regresión Logística
Breast Cancer Wisconsin Diagnostic Data Set

Este proyecto aplica técnicas de Machine Learning para clasificar tumores de mama como benignos o malignos, utilizando Regresión Logística y un flujo profesional de modelado.

📌 Objetivo

Construir un modelo interpretable que permita identificar tumores malignos, priorizando la sensibilidad (recall) debido al impacto clínico de los falsos negativos.

📂 Contenido

Exploración de datos (EDA)

Preprocesamiento

Escalamiento

Pipeline de ML

Entrenamiento de regresión logística

Métricas de evaluación

Curva ROC y Precision–Recall

Matriz de confusión

Importancia de características (odds ratios)

Análisis de errores

Tuning del umbral

🧭 Flujo del proyecto

Carga del dataset

Análisis exploratorio

Preprocesamiento y escalamiento

Entrenamiento del modelo

Evaluación

Interpretabilidad

Ajuste del umbral

Conclusiones

📊 Resultados principales
Métrica	Valor
Accuracy	~0.965
Precision	~0.975
Recall (Sens.)	~0.929
F1-Score	~0.951
AUC-ROC	>0.98

El modelo captura muy bien las relaciones lineales del dataset y muestra excelente capacidad de separación entre clases.

🧠 Interpretabilidad

Se analizaron los coeficientes del modelo y sus odds ratios, identificando qué características aumentan la probabilidad de malignidad.
Esto agrega valor clínico y explicativo.

🚨 Consideraciones clínicas

Los falsos negativos fueron pocos, pero representan el error más crítico.

Se aplicó tuning del umbral para priorizar recall.

Las decisiones finales deben complementarse con métodos más complejos y validación clínica.

📎 Dataset

El dataset proviene de:
Breast Cancer Wisconsin (Diagnostic) Dataset – UCI / sklearn

🛠 Tecnologías usadas

Python

pandas

numpy

scikit-learn

matplotlib

seaborn

🏁 Conclusiones

La regresión logística, aplicada correctamente y acompañada de análisis exhaustivo, es una herramienta poderosa para tareas de clasificación médica,
especialmente cuando es necesario un modelo interpretable y con alto rendimiento.
