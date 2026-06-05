# Análisis Inicial y Selección de Problema

## Descripción
Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre distintos conjuntos de datos para identificar sus características, calidad y posibles desafíos. A partir de este análisis, se selecciona un conjunto de datos y una problemática específica para desarrollar en etapas posteriores, justificando su relevancia y potencial de aplicación en técnicas de ciencia de datos y aprendizaje automático.

## Conjuntos de Datos Analizados
Descripción breve de los cuatro conjuntos de datos analizados.

- Churn Prediction Gym Members: Este conjunto de datos reúne información sobre el comportamiento, las características demográficas y los registros de actividad de los socios de un gimnasio. Su propósito es identificar patrones relacionados con la permanencia de los clientes y analizar los factores que influyen en su abandono o cancelación de la membresía.

- Coffee Quality Institute Arabica: El dataset reúne resultados de catas profesionales de café Arábica, integrando características organolépticas del grano con información sobre su origen geográfico, lo que permite analizar la relación entre la calidad sensorial y las condiciones de producción.

- Bike Sharing: El dataset contiene registros de uso de bicicletas públicas junto con datos meteorológicos y temporales, facilitando el análisis de las variaciones en la demanda según las condiciones ambientales y los distintos momentos del día.

- Air Quality: El dataset contiene registros horarios de contaminantes atmosféricos y datos meteorológicos capturados por sensores de gases en una ciudad italiana, facilitando el estudio de la calidad del aire y los factores que influyen en ella.

## Resumen del EDA Inicial

- Churn Prediction Gym Members: Dataset analizado completamente. Se detectaron valores faltantes, un desbalance moderado en la variable objetivo y posibles relaciones entre la edad de los miembros y el abandono de la membresía. No se encontraron duplicados ni inconsistencias categóricas relevantes.

- Coffee Quality Institute Arabica: Análisis exploratorio pendiente.

- Bike Sharing: Análisis exploratorio pendiente.

- Air Quality: Análisis exploratorio pendiente.

## Problema Seleccionado
### Descripción del problema

El problema seleccionado consiste en predecir la deserción de miembros de un gimnasio (Churn) utilizando información demográfica, características de la membresía y hábitos de entrenamiento. El objetivo es construir un modelo capaz de identificar qué usuarios tienen una mayor probabilidad de abandonar el servicio, permitiendo a la organización tomar acciones preventivas para mejorar la retención de clientes.

### Justificación

Tras analizar los cuatro conjuntos de datos disponibles, se seleccionó el problema de predicción de abandono en gimnasios debido a su relevancia práctica y a las oportunidades de análisis que ofrece. Durante el EDA se identificó una variable objetivo claramente definida (Churn), así como diversas características potencialmente relacionadas con el abandono, como la edad, la frecuencia de visitas, la duración de los entrenamientos y el tipo de membresía.

Además, el conjunto de datos presenta desafíos comunes en proyectos reales de ciencia de datos, incluyendo valores faltantes, variables categóricas, variables numéricas y un desbalance moderado en la clase objetivo. Estas características permiten aplicar distintas técnicas de preparación de datos y modelado, convirtiéndolo en un caso de estudio adecuado para un problema de clasificación supervisada.

### Objetivos específicos

- Explorar y comprender las características de los miembros del gimnasio y su relación con la variable objetivo Churn.
- Aplicar técnicas de limpieza y preprocesamiento de datos, incluyendo el tratamiento de valores faltantes, la transformación de variables y la preparación del conjunto de datos para el modelado.
- Construir y comparar modelos de clasificación que permitan predecir el abandono de los clientes con el mayor nivel de precisión posible.

## Instrucciones para Ejecutar

1. Clonar o descargar el repositorio.
2. Instalar las librerías necesarias (`pandas`, `numpy`, `matplotlib` y `seaborn`).
3. Abrir los notebooks de Jupyter incluidos en el proyecto.
4. Ejecutar las celdas en orden para reproducir el análisis exploratorio.
5. Revisar las visualizaciones, hallazgos y conclusiones obtenidas.

## Autor
Cristián Sánchez — Desarrollo, análisis y documentación del proyecto.

## Licencia

Este proyecto fue desarrollado con fines académicos y educativos.
