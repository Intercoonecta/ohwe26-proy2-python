# Análisis espacio-temporal de la productividad primaria y la actividad pesquera aparente en el entorno marino de Shiretoko, Japón

## 1. Este proyecto busca analizar la asociación espacio-temporal entre la productividad del ecosistema marino y la actividad pesquera aparente en el entorno del área marina de Shiretoko, ubicada al noreste de Hokkaido, Japón.

Se integrarán datos oceanográficos satelitales del servicio Marine Copernicus (CMEMS) con información geoespacial de actividad pesquera aparente de Global Fishing Watch (GFW), mediante herramientas de programación y análisis de datos en Python.

Se consideran datos de clorofila-a como indicador de la biomasa fitoplanctónica y, por tanto, como una variable proxy relacionada con la productividad del ecosistema marino. Estos datos se complementarán con información de actividad pesquera aparente derivada de registros del sistema de identificación automática (AIS), proporcionada por Global Fishing Watch (GFW).

Adicionalmente, se propone comparar los patrones observados dentro del área marina protegida y en sus zonas circundantes, como aproximación exploratoria a la relación entre conservación, dinámica ecológica y aprovechamiento pesquero.

## 2. Preguntas de investigación

¿Cómo se distribuye espacial y temporalmente la actividad pesquera aparente en las áreas EBSA seleccionadas de Shiretoko?

¿Qué patrones espaciales y temporales presenta la concentración superficial de clorofila-a en el área de estudio?

¿Se identifican coincidencias o asociaciones espaciales y temporales entre la variabilidad de la clorofila-a y la actividad pesquera aparente?

¿Cómo puede contribuir la integración de información oceanográfica y pesquera a la comprensión de la dinámica ecosistémica del área de estudio?

## 3. Objetivo general

Analizar la asociación espacio-temporal entre la productividad del ecosistema marino y la actividad pesquera aparente en el entorno de Shiretoko, Japón, mediante la integración de información satelital y geoespacial, explorando diferencias entre el área marina protegida y sus zonas circundantes.

## 4. Variables de estudio

### Variables oceanográficas
- Concentración superficial de clorofila-a (CHL) [biomasa de fitoplancton mediante teledetección satelital y modelos numéricos]
- Producción primaria de biomasa expresada como carbono [mide la tasa neta de carbono orgánico fijado por el fitoplancton mediante la fotosíntesis tras descontar su respiración]
- Temperatura superficial del mar (SST), como variable ambiental complementaria

### Variables pesqueras
- Horas de actividad pesquera aparente.
- Distribución espacial de la actividad pesquera.
- Distribución de la actividad según su localización dentro o fuera del área protegida.

## 5. Fuentes de información

### Copernicus Marine Service
Fuente de información oceanográfica satelital y productos biogeoquímicos.

Variables de interés:
*Clorofila-a.
*Producción primaria de biomasa expresada como carbono.
*Temperatura superficial del mar (complementaria).

Sitio: https://data.marine.copernicus.eu/

### Global Fishing Watch
Fuente de información geoespacial sobre actividad pesquera aparente, estimada a partir de información AIS y otros datos de seguimiento disponibles.

Variables de interés:
*Horas de actividad pesquera aparente.
*Distribución espacial de la actividad.
*Información temporal de la actividad pesquera.

Sitio: https://globalfishingwatch.org/

## 6. Área de estudio

El área de estudio comprende dos polígonos correspondientes a áreas de importancia ecológica y biológica (EBSA, por sus siglas en inglés), localizados en el entorno marino de Shiretoko, Hokkaido, Japón:

EBSA 10401: Shiretoko (Shari–Utoro) side coast.

EBSA 10402: Shiretoko (Rausu) side coast.

La delimitación espacial se encuentra representada en el archivo geográfico Shiretoko_EBSA_10401_10402.geojson, utilizado para realizar las consultas y los análisis geoespaciales.

## 7. Periodo de análisis

Se propone trabajar con los años 2020 y 2025, sujetos a disponibilidad y consistencia de los datos.
Frecuencia temporal: agregaciones mensuales.
Se buscará mantener una resolución espacial y temporal compatible entre las fuentes de información.

## 8. Metodología general

a. Delimitación geográfica del área de estudio y de las zonas de comparación.
b. Identificación de productos biogeoquímicos de CMEMS. 
c. Consulta y obtención de información de actividad pesquera aparente de GFW.
d. Descarga y procesamiento de datos mediante Python.
e. Homogeneización de las variables espaciales y temporales.
f. Exploración estadística y análisis descriptivo.
g. Elaboración de mapas de distribución espacial.
h. Comparación temporal y espacial de las variables.
i. Evaluación exploratoria de asociaciones estadísticas.
j. Interpretación de los resultados en el contexto de conservación y gestión marina.

## 9. Herramientas y tecnologías #aun por definir 

*Python.
*JupyterHub / Jupyter Notebook.
*Pandas y NumPy.
*Xarray.
*Matplotlib y Seaborn.
*GeoPandas y Cartopy.
*SciPy.
*APIs de Copernicus Marine y Global Fishing Watch.

## 10. Resultados esperados

- Visualización espacial de la concentración de clorofila-a y, si es viable, de la producción primaria.
- Mapas de intensidad de actividad pesquera aparente.
- Identificación de patrones de coincidencia espacial entre productividad y actividad pesquera.
- Comparación de la actividad pesquera aparente dentro y fuera del área marina protegida.
- Exploración de asociaciones estadísticas entre variables oceanográficas y pesqueras.
- Procesamiento y análisis de datos en Python.

## 11. Limitaciones

- La actividad pesquera aparente de GFW se estima a partir de datos de seguimiento de embarcaciones y no representa la totalidad de la actividad pesquera.
- La clorofila-a es un indicador de biomasa fitoplanctónica y no una medición directa de producción primaria neta ni de abundancia de peces.
- La productividad primaria no se traduce necesariamente en disponibilidad inmediata de recursos pesqueros, debido a las relaciones tróficas y las variaciones espacio-temporales.
- La interpretación de diferencias dentro y fuera del área protegida deberá considerar las características de sus medidas de manejo y las restricciones efectivamente aplicables.

## 12. Estado del proyecto

**Etapa actual:** Planeación y selección de fuentes de información.

Próximas actividades:
- [ ] Delimitar el área de estudio.
- [ ] Seleccionar los productos de Copernicus.
- [ ] Revisar disponibilidad histórica de datos.
- [ ] Obtener acceso a la API de Global Fishing Watch.
- [ ] Realizar una prueba de descarga de ambas fuentes.
- [ ] Definir la resolución espacial y temporal definitiva.
- [ ] Explorar los datos. 

**Integrantes:** Isabel Pérez, Victor Goméz, María Alejandra Cifuentes y Keynie Cauich-Tome. 
