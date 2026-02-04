🛍️ User Spending Data — From Raw Data to Reliable Insights
Data Preprocessing & Structuring
📌 Contexto del proyecto

En muchos proyectos reales de análisis de datos, el principal desafío no es analizar, sino preparar datos desordenados, inconsistentes y difíciles de usar.

En este proyecto trabajé con datos de gasto de usuarios entregados por un cliente en un formato poco estructurado (listas anidadas de Python), con el objetivo de transformarlos en un dataset limpio, consistente y listo para análisis y toma de decisiones.

El foco no está en los resultados finales, sino en la calidad del dato, que es la base de cualquier análisis confiable.

🎯 Objetivo del proyecto

Depurar y estandarizar datos de gasto a nivel usuario.

Detectar y corregir inconsistencias en formato y tipos de datos.

Validar información proveniente de fuentes no estructuradas.

Organizar los datos para que puedan ser analizados fácilmente en etapas posteriores.

📊 Descripción de los datos

El dataset fue proporcionado por un cliente y contiene información a nivel de usuario con estructuras anidadas y formatos inconsistentes.

Incluye:

user_id → identificador único del usuario

user_name → nombre del usuario

user_age → edad

fav_categories → lista de categorías de productos favoritas

total_spendings → lista de montos gastados por categoría

Los datos originales presentaban problemas comunes del mundo real:

formatos no uniformes

tipos de datos incorrectos

listas desalineadas

valores inesperados

Lo que hacía imposible un análisis directo sin un preprocesamiento adecuado.

🧠 Enfoque de trabajo

El proyecto se abordó como lo haría un analista en un entorno profesional:

Evaluación de la calidad del dato
Se identificaron inconsistencias, errores y problemas estructurales antes de cualquier análisis.

Limpieza y estandarización

Normalización de texto

Corrección de formatos

Conversión de tipos de datos (por ejemplo, de float a int)

Validación y manejo de errores
Se incorporaron controles para asegurar que los datos fueran coherentes y robustos frente a entradas incorrectas.

Reestructuración de la información
Las listas y estructuras anidadas fueron reorganizadas para facilitar su uso en análisis posteriores.

Generación de datos listos para análisis
Se crearon resúmenes claros y consistentes que permiten avanzar directamente a EDA o modelado.

📈 Resultados principales

Dataset limpio, consistente y confiable

Datos preparados para análisis exploratorio y visualización

Mayor robustez frente a datos no estructurados

Reducción de errores y ambigüedades en la información original

💡 Por qué este proyecto es relevante

Este proyecto refleja un escenario muy común en roles de Data Analyst:

Los datos no llegan listos

Existen errores, formatos inconsistentes y estructuras poco claras

El valor está en ordenar, validar y preparar antes de analizar

Demuestra la capacidad de transformar datos crudos en una base sólida para decisiones basadas en evidencia.

🛠️ Herramientas utilizadas

Python

Pandas

NumPy

Jupyter Notebook

GitHub para documentación y versionado

📂 Estructura del proyecto
├── 01_user_spending_data_preprocessing.ipynb
├── README.md
└── requirements.txt
