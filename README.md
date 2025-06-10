# Challenge-TelecomX-LATAM
Análisis de Cancelación de Clientes (Churn)


    Descripción del Proyecto
Este proyecto analiza los datos de clientes de TelecomX en Latinoamérica para identificar patrones de cancelación 
de servicios (churn). El proceso incluye extracción, transformación, análisis exploratorio y generación de insights 
para reducir la evasión de clientes.


    Tecnologías Utilizadas
Python 3

Pandas (para manipulación de datos)

Seaborn/Matplotlib (para visualizaciones)

Google Colab (entorno de ejecución)


     Estructura del Proyecto

Extracción: Carga de datos desde archivo JSON (TelecomX_Data.json)

Transformación:

Normalización de datos anidados

Limpieza y estandarización de valores

Traducción de columnas a español

Ingeniería de características (ej: cálculo de cargo diario)

Análisis:

Estadísticas descriptivas

Visualización de patrones de cancelación

Comparación entre grupos de clientes

Resultados: Informe con conclusiones y recomendaciones

         Principales Hallazgos
26.8% de tasa de cancelación

Clientes con contrato mensual tienen mayor probabilidad de cancelar

Antigüedad promedio menor en clientes que cancelan (~19 meses vs ~37 meses)

Métodos de pago electrónicos asociados a mayor churn


    Visualizaciones Clave

Distribución de cancelación (Sí/No)

Boxplots de Cargo Total y Antigüedad por estado

Histogramas comparativos

Análisis por variables categóricas (servicios contratados, tipo de contrato, etc.)

           Informe Completo

El análisis detallado con conclusiones y recomendaciones estratégicas se encuentra en el notebook principal:
TelecomX_LATAM_base.ipynb

     Recomendaciones Estratégicas

Incentivar contratos anuales

Mejorar experiencia en primeros 3 meses

Alertas tempranas para clientes con bajo uso

Campañas específicas por método de pago

Desarrollo de modelo predictivo de churn

      Notas Adicionales
Dataset original: TelecomX_Data.json

Todas las transformaciones quedan documentadas en el proceso ETL

Columnas traducidas al español para mejor comprensión del negocio

      Cómo Ejecutar

Subir el archivo JSON a Colab

Ejecutar celdas en orden

Los gráficos se mostrarán online
