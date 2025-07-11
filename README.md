Análisis de Evasión de Clientes (Churn) - Telecom X

📖 Descripción del Proyecto

Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) sobre un conjunto de datos de la empresa ficticia "Telecom X". El objetivo principal es identificar los factores y patrones clave que influyen en la decisión de los clientes de cancelar sus servicios (churn). Los insights obtenidos a partir de este análisis pueden ser utilizados por la empresa para desarrollar estrategias de retención más efectivas.

🛠️ Tecnologías Utilizadas

Python 3

Pandas: Para la manipulación y limpieza de datos.

Matplotlib & Seaborn: Para la generación de visualizaciones y gráficos.

Google Colab / Jupyter Notebook: Como entorno de desarrollo.

📂 Estructura del Proyecto

El análisis se encuentra completamente contenido en el notebook analisis_churn_telecom_x.ipynb (o el nombre que le hayas dado) y sigue la siguiente estructura:

Carga y Limpieza de Datos: Importación de los datos desde la fuente, manejo de la estructura anidada del JSON, corrección de tipos de datos y valores nulos.

Tratamiento de Inconsistencias: Verificación de datos duplicados y corrección de valores categóricos.

Ingeniería de Características: Creación de nuevas columnas para enriquecer el análisis.

Estandarización y Transformación: Conversión de datos categóricos a formato numérico y renombrado de columnas para mayor claridad.

Análisis Descriptivo y Visual: Generación de estadísticas y gráficos para explorar la distribución de los datos y las relaciones entre las variables y la tasa de churn.

Informe Final: 

Un resumen con las conclusiones, insights y recomendaciones estratégicas basadas en los hallazgos.

🚀 Cómo Utilizar el Proyecto

Clona o descarga este repositorio.

Abre el archivo .ipynb en un entorno compatible como Google Colab o Jupyter Notebook.

Ejecuta las celdas en orden secuencial para replicar el análisis completo.

📊 Principales Hallazgos

Tipo de Contrato: Los clientes con contratos "mes a mes" presentan una tasa de churn significativamente más alta.

Antigüedad del Cliente (Tenure): Los clientes nuevos (con baja antigüedad) son más propensos a cancelar el servicio.

Cargos Mensuales: Existe una correlación entre cargos mensuales más elevados y una mayor probabilidad de evasión.
