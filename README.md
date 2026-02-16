📉 Telecom X – Análisis de Evasión de Clientes (Churn)
📌 Descripción del proyecto

Telecom X enfrenta un alto nivel de cancelaciones y necesita entender por qué los clientes abandonan el servicio. Este proyecto, almacenado en el repositorio Challenge_TelecomX_LATAM, busca recopilar, limpiar, transformar y analizar los datos disponibles para detectar patrones de evasión. Con un enfoque ordenado y práctico, se espera entregar información que sirva como base para modelos predictivos y estrategias de retención.

🎯 Objetivos

Importar los datos desde la API de Telecom X en formato JSON.

Aplicar un flujo ETL sencillo (Extracción, Transformación y Carga) para preparar el dataset.

Explorar la estructura del conjunto de datos y sus tipos de variables.

Identificar las variables más relevantes asociadas al churn.

Generar visualizaciones que permitan observar patrones y tendencias.

Elaborar conclusiones e insights que apoyen la toma de decisiones.

🧰 Tecnologías utilizadas

Python 3.x como lenguaje de programación.

Pandas para manipulación y análisis de datos.

Matplotlib y Seaborn para visualizaciones.

Google Colab como entorno de ejecución del notebook.

🗂️ Estructura del repositorio
Challenge_TelecomX_LATAM/
├── notebooks/
│   └── churn_analysis.ipynb
└── README.md

▶️ Cómo ejecutar el proyecto

Clona este repositorio o abre el notebook directamente en Google Colab.

Ejecuta las celdas de churn_analysis.ipynb en orden. El notebook importa los datos desde la API, por lo que no es necesario descargar archivos manualmente.

Revisa los gráficos y resultados generados para comprender las tendencias y patrones de evasión.

📊 Proceso realizado

Extract: Cargar el JSON desde la API de Telecom X y convertirlo a un DataFrame de Pandas.

Transform: Inspeccionar tipos de datos, limpiar valores faltantes y duplicados, crear nuevas variables (como el cálculo de la cuenta diaria a partir de la facturación mensual) y, si es necesario, codificar variables categóricas.

Load & Analysis: Realizar un análisis exploratorio con métricas descriptivas, visualizar la distribución de la variable Churn y analizar su relación con otras variables categóricas y numéricas. Finalmente, elaborar un informe con conclusiones y recomendaciones.

💡 Resultados esperados

Al finalizar el análisis se espera identificar perfiles de clientes con mayor probabilidad de cancelar el servicio, así como los factores que influyen en su decisión. Estos hallazgos permitirán diseñar acciones de fidelización y prever la evasión de manera más efectiva.

🚀 Autor

Cristian Flores Bernal
