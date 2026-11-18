# Análisis espacio-temporal de productividad (clorofila-a) y la actividad pesquera en las costas de Japón

## Este proyecto busca analizar la asociación espacial y temporal entre la concentración superficial de clorofila-a y la distribución de la actividad pesquera en aguas de Japón, mediante la integración de información satelital y datos geoespaciales.

Se utilizarán datos oceanográficos del programa Copernicus Marine Service y registros de actividad pesquera de Global Fishing Watch (GFW), procesados mediante herramientas de programación en Python.

## 2. Preguntas de investigación

¿Existe una asociación espacial y temporal entre la concentración de clorofila-a en la superficie del océano y las zonas de mayor presencia de flotas pesqueras?

¿Qué limita a la productividad (clorofila-a)? 
¿La temperatura puede estar relacionada con una disminución de clorofila-a? 


## 3. Objetivo general

Analizar la asociación espacio-temporal entre la variabilidad de la concentración superficial de clorofila-a y la distribución de la actividad pesquera. 

## 4. Variables de estudio

### Variables oceanográficas
- Concentración superficial de clorofila-a (CHL).
- Temperatura superficial del mar (SST)*?

### Variables pesqueras
- Intensidad de actividad pesquera aparente.
- Distribución espacial de las flotas pesqueras.

## 5. Fuentes de información

### Copernicus Marine Service
Fuente de información oceanográfica y productos satelitales.

Variables de interés:
- Clorofila-a.
- Temperatura superficial del mar- ? 

Sitio: https://data.marine.copernicus.eu/

### Global Fishing Watch
Fuente de información geoespacial sobre actividad pesquera aparente y distribución de embarcaciones detectadas mediante AIS.

Sitio: https://globalfishingwatch.org/

## 6. Área de estudio

Región preliminar:
Hokkaido y norte de Japón. 
Aguas cercanas del área marina protegida Atolón de Okinotorishima. 


*Aún definiendo la delimitación geográfica definitiva, según la distribución de la actividad pesquera y la disponibilidad de información oceanográfica.

## 7. Periodo de análisis

Años de contraste: (año muy atras), 2020, 2025. 

Frecuencia de análisis propuesta: promedios mensuales en los años a contrastar.


## 8. Metodología general

1. Identificación y selección de productos oceanográficos en Copernicus Marine.
2. Descarga de datos de concentración de clorofila-a y temperatura superficial.
3. Consulta y descarga de información pesquera de Global Fishing Watch.
4. Delimitación del área geográfica de estudio.
5. Homogeneización de las variables espaciales y temporales.
6. Integración de las bases de datos.
7. Análisis exploratorio. 
8. Elaboración de mapas y visualizaciones.
9. Análisis estadístico.
10. Interpretación de los patrones identificados.

## 9. Herramientas y tecnologías #aun por definir 

- Python
- Jupyter Notebook
- Pandas

## 10. Resultados esperados

- Mapas de concentración de clorofila-a.
- Mapas de intensidad de actividad pesquera.
- Identificación de zonas de coincidencia espacial.
- Comparación de patrones entre periodos.
- Evaluación de asociaciones estadísticas entre variables oceanográficas y pesqueras.

## 11. Limitaciones

- La información AIS no representa la totalidad de las embarcaciones pesqueras.
- La concentración de clorofila-a es un indicador de biomasa fitoplanctónica, no una medición directa de abundancia de peces.
- Verificar que realmente exista una relación estadistica 

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


**Integrantes:** Isabel Pérez, Victor Goméz, María Cifuentes y Keynie Cauich-Tome. 

