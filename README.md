# TelecomX-LATAM
📊 Análisis de Evasión de Clientes (Churn) – TelecomX
🧠 Descripción del proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (churn) en la empresa ficticia TelecomX, utilizando técnicas de análisis exploratorio de datos (EDA) y segmentación de riesgo.

A partir de los datos históricos de clientes, se identifican patrones asociados al abandono, se construyen variables derivadas y se desarrolla un score de riesgo temprano, orientado a apoyar decisiones estratégicas de retención.

🎯 Objetivos

Analizar la distribución del churn en la base de clientes.

Identificar variables asociadas a una mayor probabilidad de abandono.

Explorar diferencias entre clientes que permanecen y los que cancelan.

Construir un score de riesgo temprano de evasión.

Generar insights accionables para estrategias de retención.

📁 Dataset

Archivo original: TelecomX_Data.json

Fuente: Repositorio público
🔗 https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json

Formato: JSON anidado

Contenido: Información demográfica, contractual, servicios contratados y facturación de clientes.

⚠️ El dataset fue preprocesado para desanidar estructuras, estandarizar variables y eliminar registros con estado de churn desconocido.

🛠️ Tecnologías utilizadas

Python 3

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔄 Flujo del análisis

Carga y exploración inicial de datos

Limpieza y preparación

Desanidado del JSON

Manejo de valores nulos

Estandarización de variables binarias

Ingeniería de variables

Cargo diario

Cliente temprano

Variables combinadas de servicios

Análisis descriptivo

Variables numéricas y categóricas

Comparación churn vs no churn

Análisis de evasión

Por contrato, servicios, método de pago

Por combinación de servicios de internet

Score de riesgo temprano

Segmentación de clientes en niveles de riesgo

Cálculo de tasa de abandono por segmento

📈 Principales resultados

El churn está fuertemente asociado a:

Contratos mensuales (Month-to-month)

Baja antigüedad del cliente

Menor adopción de servicios de valor agregado

El score de riesgo temprano permite:

Priorizar clientes con mayor probabilidad de abandono

Identificar segmentos de alto impacto para estrategias de retención

El mayor valor estratégico se encuentra en clientes de riesgo medio-alto, no solo en los extremos.

📊 Estructura del notebook

El notebook está organizado de forma secuencial y comentada, permitiendo:

Reproducibilidad del análisis

Fácil seguimiento del flujo lógico

Comprensión tanto técnica como de negocio

🚀 Próximos pasos

Implementar modelos predictivos de churn (Logistic Regression, Random Forest).

Validar el score con métricas de desempeño.

Automatizar el monitoreo de riesgo.

Integrar variables de comportamiento (si están disponibles).

👤 Autora

Ivonne Romero
Ciencias de la Tierra | Ciencias Ambientales
Interés en Data Science, sostenibilidad y análisis de riesgo

📄 Licencia

Este proyecto se comparte con fines educativos y de portafolio personal.
