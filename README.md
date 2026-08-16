# Mobility & Economy Analysis – Sprint 5

Este repositorio contiene el análisis enfocado en estudiar la relación entre la movilidad urbana y los indicadores económicos de ciudades a nivel internacional.
El proyecto utiliza datos de TomTom Traffic Index y OECD Cities para analizar indicadores de tráfico, tiempos de viaje, congestión, PIB per cápita, desempleo, población y calidad del aire. El objetivo principal es identificar patrones que puedan ayudar a determinar qué ciudades podrían requerir mayor atención e inversión en infraestructura de transporte.


## Objetivo del proyecto

Evaluar cómo los indicadores de movilidad urbana se relacionan con diferentes indicadores de productividad y condiciones económicas en las ciudades analizadas.


## Datos utilizados

El proyecto utiliza dos fuentes principales:
TomTom Traffic Index → indicadores de tráfico, congestión y tiempos de viaje.
OECD Cities → indicadores económicos, demográficos y ambientales.
El análisis se concentra en los datos correspondientes a 2024.


## Principales variables

* Movilidad urbana
* Congestión
* Retrasos por tráfico
* Longitud de congestiones
* Número de congestiones
* Tiempo de viaje
* Tiempo adicional de viaje
* Economía y contexto urbano
* PIB per cápita
* Tasa de desempleo
* Población
* Calidad del aire (PM2.5)
  

## Tecnologías utilizadas

- **Python** – Lenguaje principal del análisis.
  
- **Pandas** – Manipulación y transformación de datos.

- **NumPy** – Operaciones numéricas.

- **Matplotlib** – Visualización de datos.

- **Jupyter Notebook** – Desarrollo y documentación del análisis.

- **Google Colab** – Ejecución y presentación del notebook.

- **GitHub** – Control y documentación del proyecto.


## Principales hallazgos

- Se identificaron diferencias relevantes en los niveles de congestión entre las ciudades analizadas.

- Los indicadores de movilidad presentan variaciones importantes en tiempos de viaje y retrasos.
  
- Se observaron diferencias entre las condiciones de movilidad y los indicadores económicos de las ciudades.
  
- La integración de indicadores de movilidad y economía permite obtener una visión más completa del contexto urbano.


## Contenido del repositorio

`notebooks/S5_Iadb_mobility_economy_project_student(1).ipynb`
  - Notebook principal con exploración, limpieza, transformación, integración y visualización.

- `labd_mobility_economy_2024_clean.csv`
  - Dataset final generado después de integrar los indicadores de movilidad y economía.


## Cómo reproducir el análisis

Abre notebooks/S5_ladb_mobility_economy_project_student(1).ipynb.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TTHpoYBEXpmCYYbrxsUkL1Um2gQHYEvu?usp=sharing)

Ejecuta las celdas en orden.
El notebook carga los datasets utilizados para el análisis de movilidad urbana y economía.
Al finalizar, se genera el dataset limpio ladb_mobility_economy_2024_clean.csv.

## Conclusiones

El análisis demuestra la importancia de combinar indicadores de movilidad y variables económicas para obtener una visión más completa de las condiciones urbanas.
La integración de diferentes fuentes permite identificar patrones que no serían visibles al analizar cada dataset de manera independiente y proporciona una base para futuros análisis de infraestructura, movilidad y desarrollo urbano.


## Autor

**César Augusto Mercado**

Analista de Datos Jr. | Comunicador Social y Periodista

📍 Bogotá, Colombia

Actualmente en formación en **Análisis de Datos**, con experiencia en comunicación, elaboración de informes, análisis de información y desarrollo organizacional.

Este proyecto fue desarrollado como parte del programa de formación en **TripleTen – Análisis de Datos**.



