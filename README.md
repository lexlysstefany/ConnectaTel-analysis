# ConnectaTel-analysis

Este repositorio contiene el análisis realizado para el caso de estudio **ConnectaTel**, enfocado en limpieza de datos, análisis exploratorio y segmentación de clientes.

El dataset incluye información de usuarios y registros de uso del servicio, presentando valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular escenarios reales en la industria de telecomunicaciones.


## Contenido del repositorio

* `notebooks/connectatel_analysis.ipynb`
  → Notebook principal con limpieza de datos, análisis exploratorio (EDA), histogramas, boxplots, segmentación de clientes y conclusiones de negocio.


## Cómo abrir el notebook en Google Colab

1. Abre el archivo `.ipynb` en GitHub.
2. Haz clic en **Open in Colab**.


## Cómo reproducir el análisis

1. Abre `notebooks/connectatel_analysis.ipynb`
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente los datasets desde la carpeta.



## Objetivo del análisis

* Identificar problemas de calidad de datos.
* Limpiar y preparar los datos para análisis.
* Detectar valores nulos, sentinels y registros inconsistentes.
* Analizar patrones de comportamiento de clientes.
* Identificar segmentos según edad y nivel de uso.
* Detectar outliers y usuarios de alto valor (“whales”).
* Generar recomendaciones de negocio para optimizar planes y servicios.



## Principales análisis realizados

* Distribución de usuarios por edad.
* Comparación entre planes Basic y Premium.
* Análisis de mensajes enviados.
* Análisis de llamadas realizadas.
* Distribución de minutos por llamada.
* Detección de outliers mediante boxplots e IQR.
* Segmentación por edad y nivel de uso.



## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Google Colab



## Principales hallazgos

* Los usuarios Premium presentan mayor intensidad de uso en llamadas y mensajes.
* Los adultos mayores tienen una participación importante dentro del plan Premium.
* Se identificaron usuarios extremos con llamadas de larga duración.
* El segmento de uso medio representa la mayor parte de la base de clientes.
* Existen oportunidades de negocio para crear planes especializados según edad y nivel de consumo.



## Autor

Proyecto desarrollado por Lexlys Avendaño como parte de un proyecto de análisis de datos enfocado en telecomunicaciones y segmentación de clientes.

