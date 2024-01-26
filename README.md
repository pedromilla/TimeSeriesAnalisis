## Predicción de Temperaturas: Un Análisis Detallado de Series Temporales

En este proyecto de predicción de temperaturas, se llevó a cabo un análisis exhaustivo utilizando modelos LSTM y Prophet para anticipar patrones climáticos futuros.

## Recopilación y Preparación de Datos:

Se inició el proyecto recopilando datos históricos de temperaturas en la cuenca de Los Lagos ubicada en la Región de Los Ríos, desde enero de 1979 hasta abril de 2020. Posteriormente, se exploraron y prepararon los datos seleccionando variables relevantes, como las temperaturas máximas y mínimas diarias. Además, se llevó a cabo una limpieza de datos para garantizar la coherencia y calidad de la información.

## Análisis Exploratorio con Visualizaciones:

Se realizaron visualizaciones detalladas para explorar patrones y tendencias en los datos. Estas visualizaciones proporcionaron una comprensión inicial de la variabilidad de las temperaturas a lo largo del tiempo.

## Pruebas Estadísticas:

Se aplicaron pruebas estadísticas para evaluar la estacionariedad de la serie temporal y otros aspectos clave. Esto contribuyó a la selección adecuada de modelos y métodos de predicción.

## Predicciones con LSTM:

Implementamos un modelo de red neuronal LSTM para realizar predicciones de temperatura. Utilizando datos históricos hasta abril de 2020 agrupados mensualmente, el modelo se entrenó y se realizaron predicciones para los meses de septiembre de 2023 a enero de 2024.

## Predicciones con Prophet:

Se utilizó el modelo Prophet de Facebook para realizar predicciones de temperatura diarios. Al igual que con LSTM, el modelo se entrenó con datos históricos y se extendieron las predicciones para los mismos meses.

## Evaluación y Comparación de Modelos:

Se llevaron a cabo evaluaciones de desempeño para ambos modelos utilizando métricas específicas para series temporales. Además, se compararon las predicciones de LSTM y Prophet con los valores reales de temperatura.

## Visualización y Análisis de Predicciones:

Se crearon visualizaciones detalladas para presentar las predicciones de ambos modelos junto con los valores reales. Se destacaron las áreas de confianza, tendencias y variaciones significativas en las temperaturas pronosticadas.

## Conclusión y Resultados:

Se presentó una conclusión detallada que resume los resultados obtenidos de ambas metodologías. Se proporcionaron insights sobre la eficacia de los modelos en la predicción de temperaturas y cómo estos resultados pueden ser útiles en la planificación y toma de decisiones relacionadas con el clima.

Este proyecto representa un paso significativo hacia la comprensión y anticipación de patrones climáticos, proporcionando información valiosa para la planificación y adaptación a condiciones térmicas futuras.
