Análisis de Clientes y Uso de Servicios en ConnectaTel
Objetivo del proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel mediante información demográfica y de uso de servicios móviles, con el fin de:
    - Identificar patrones de consumo.
    - Detectar problemas de calidad en los datos.
    - Segmentar usuarios según edad y nivel de uso.
    - Generar insights de negocio para apoyar decisiones comerciales y estratégicas.
    - Proponer mejoras y oportunidades para los planes actuales.

Datasets utilizados
Se trabajó principalmente con los siguientes datasets:
plans.csv: contiene información sobre el uso de los planes actuales. 
users_latam.csv: contiene información demográfica y de suscripción de los clientes.
usage.csv: contiene información del uso de servicios por parte de los usuarios.

Etapas del análisis realizadas
1. Exploración inicial de datos (EDA)
Revisión de estructura de datasets.
Identificación de tipos de variables.
Exploración de valores únicos y estadísticas descriptivas.
2. Limpieza y calidad de datos
Detección de valores nulos.
Identificación de valores inválidos y sentinels (-999, "?").
Conversión de columnas de fecha.
Corrección de fechas fuera de rango.
Evaluación de nulos estructurales.
3. Análisis exploratorio
Distribuciones de variables numéricas y categóricas.
Histogramas y boxplots.
Detección de outliers mediante IQR.
Comparación de comportamiento según tipo de plan.
4. Feature Engineering
Creación de nuevas variables:
cant_mensajes
cant_llamadas
cant_minutos_llamada
grupo_uso
grupo_edad
5. Segmentación e insights
Identificación de segmentos de clientes.
Evaluación de usuarios de alto valor.
Recomendaciones estratégicas para negocio.

Cómo ejecutar el notebook
Opción 1: Google Colab
Abrir Google Colab:
https://colab.research.google.com/
Subir el notebook .ipynb.
Subir los datasets requeridos (users.csv, usage.csv).
Ejecutar las celdas en orden.
Opción 2: Jupyter Notebook
Requisitos:
Python 3.x
pandas
numpy
seaborn
matplotlib
Instalación de librerías:
pip install pandas numpy seaborn matplotlib
Ejecutar notebook:
jupyter notebook
🔁 Guía de reproducción
Cargar datasets.
Importar librerías.
Ejecutar limpieza de datos.
Validar nulos y valores inválidos.
Realizar análisis exploratorio.
Crear variables agregadas y segmentos.
Generar visualizaciones.
Revisar insights y conclusiones ejecutivas.
📊 Resultados principales
Se identificaron problemas de calidad en edad, ciudades y fechas.
Los usuarios se segmentaron en bajo, medio y alto uso.
Los clientes de alto consumo representan una oportunidad comercial importante.
El plan Básico concentra la mayor cantidad de usuarios.
Los patrones de consumo pueden utilizarse para diseñar planes más personalizados y estrategias de fidelización.
🚀 Recomendaciones
Crear planes segmentados según nivel de uso.
Diseñar estrategias de upselling hacia Premium.
Mejorar validaciones de captura de datos.
Implementar análisis continuo de comportamiento de usuarios.
