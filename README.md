# ANALISIS-DE-DATOS-
# Análisis de clientes de ConnectaTel

Proyecto del bootcamp de Análisis de Datos de TripleTen.

## Objetivo

Explorar y limpiar los datos de ConnectaTel para analizar el uso de llamadas y mensajes, detectar valores atípicos y segmentar a los clientes por edad y nivel de actividad.

## Datasets utilizados

- `plans.csv`: precios y beneficios de los planes.
- `users_latam.csv`: información de 4,000 clientes, incluyendo edad, ciudad, plan y fechas de registro y baja.
- `usage.csv`: 40,000 registros de llamadas y mensajes.

El periodo de referencia del análisis es hasta 2024.

## Etapas del análisis

1. Carga y exploración de los tres datasets.
2. Identificación de valores ausentes, marcadores inválidos y fechas inconsistentes.
3. Limpieza de edades, ciudades y fechas.
4. Agrupación del consumo por cliente y unión con la información de usuarios.
5. Cálculo de estadísticas descriptivas.
6. Visualización de distribuciones mediante histogramas y boxplots.
7. Detección de outliers mediante el método IQR.
8. Segmentación por edad y nivel de uso.
9. Elaboración de conclusiones y recomendaciones comerciales.

## Herramientas

Python, Jupyter Notebook, pandas, NumPy, Seaborn y Matplotlib.

## Cómo ejecutar el notebook

1. Descarga el archivo `.ipynb` de este repositorio y los tres datasets.
2. Abre el notebook en Jupyter Notebook o Google Colab.
3. Instala las dependencias si no están disponibles:

   ```python
   %pip install pandas numpy seaborn matplotlib 
