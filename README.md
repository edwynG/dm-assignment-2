# Air Quality Data in India - EDA
Usando el dataset `data/city_day.csv`, realice un análisis exploratorio en un notebook de Python (Jupyter).

### Rúbrica de evaluación
1. **Descripción del dataset:** Reporte número de filas, columnas y tipos de datos.

3. **Estadísticas descriptivas:** Presentar una tabla con las siguientes medidas para las variables numéricas: Media, Mediana, Desviación estándar, Mínimo, Máximo

4. **Histogramas:** Generar histogramas para al menos 3 variables numéricas para visualizar la distribución de sus valores.

5. **Box plots:** Generar box plots para al menos 2 variables numéricas e identificar la presencia de valores atípicos (outliers).

6. **Análisis de correlación:**
    - Matriz de correlación presentada como un heatmap para visualizar las relaciones entre variables.
    - Scatter plot del par de variables con mayor correlación para observar su relación directa.

## Resumen del EDA
Al analizar el conjunto de datos, vemos que tiene una buena estructura, pero también varios problemas importantes que harán necesario limpiar y preparar bien la información antes de usarla. Por ejemplo, hay muchas faltas de datos en variables como el xileno, las partículas contaminantes (PM2.5 y PM10) tienen una distribución muy desigual con muchos valores altos raros, y hay valores extremos que hacen que el Índice de Calidad del Aire (AQI) suba mucho. Además, algunas sustancias químicas están muy relacionadas entre sí. Todos estos puntos deben tratarse con cuidado para poder encontrar patrones confiables o crear modelos que funcionen bien.
