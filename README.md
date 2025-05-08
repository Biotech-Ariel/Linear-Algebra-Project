# Linear-Algebra-Project

Análisis Predictivo para Compañía de Seguros – Sure Tomorrow
La aseguradora Sure Tomorrow busca aprovechar técnicas de Machine Learning para resolver varias tareas estratégicas relacionadas con sus clientes y servicios.

🎯 Objetivos del Proyecto:

Segmentación de Clientes: Identificar clientes similares a uno dado, para mejorar las campañas de marketing personalizado.

Clasificación Binaria: Predecir si un nuevo cliente recibirá o no beneficios del seguro (modelo predictivo vs. modelo dummy).

Regresión: Estimar el número de beneficios de seguro que un cliente podría recibir.

Ofuscación de Datos: Proteger datos personales mediante técnicas de transformación sin comprometer el rendimiento del modelo.

📊 Datos Utilizados:

Archivo: insurance_us.csv

Variables:

gender, age, income, family_members (features)

insurance_benefits (target para regresión)

Se realizaron renombramientos y transformación de tipos de datos (por ejemplo, edad a entero).

🔍 Procesamiento y Exploración:

Análisis descriptivo para validar la integridad de los datos.

Exploración de relaciones entre características y el objetivo (insurance_benefits).

🤖 Técnicas de Machine Learning:

Modelos Supervisados:

Vecinos más cercanos (k-NN)

Regresión Lineal

Modelos de Clasificación para tareas binarias

Evaluación:

Métricas de clasificación (Accuracy, Precision, Recall)

Métricas de regresión (MAE, MSE, RMSE)

Ofuscación de Datos:

Algoritmo de transformación que protege variables sensibles (e.g., ingresos) sin afectar el rendimiento del modelo.

✅ Conclusiones:

Se logró desarrollar modelos útiles tanto para clasificación como para regresión.

La técnica de enmascaramiento de datos fue efectiva, manteniendo la calidad del modelo tras la transformación.

Este enfoque puede escalarse para proteger información sensible en entornos reales de producción.
