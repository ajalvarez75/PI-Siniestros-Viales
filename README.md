# Proyecto individual 2: Análisis de Homicidios en Incidentes de Tráfico en CABA, Argentina.

## Introducción

Este proyecto simula el rol de un Analista de Datos en el equipo de una empresa consultora. El Observatorio de Movilidad y Seguridad Vial (OMSV), un centro de estudios bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA), ha solicitado la elaboración de un proyecto de análisis de datos.

Para Comenzar con el análisis de puso a disposición el archivo homicidios.xlsx de la pagina https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales el cual contiene datos de siniestros viales de la ciudad de CABA la cual es la capital de Argentina, esta ciudad desde hace muchos años ha tenido su crecimiento poblacional limitado debido a que se encuentra ya rodeada por otras ciudades y ademas limita con el rio de la Plata.

En este contesto los accidentes o siniestros viales ocurren dentro las 15 comunas que conforman la ciudad actualmente su población es de 3.121.707 según el informe Censo Nacional de Población, Hogares y Viviendas 2022 publicado por el El Instituto Nacional de Estadística y Censos (INDEC).

**Objetivo:** Generar información que ayude a las autoridades locales a tomar medidas para reducir la cantidad de víctimas mortales en incidentes de tráfico en CABA.

**Datos Disponibles:** Conjunto de datos sobre homicidios en incidentes de tráfico en la Ciudad de Buenos Aires durante el periodo 2016-2021.

Este archivo tiene dos pestañas con tablas de datos de donde se va a analizar la información, una llamada HECHOS y la otra llamada VICTIMAS y dos pestañas mas que son los diccionarios de cada una de las pestañas.

## Productos Finales

- **Informe:** El informe en cuestión se realizo en un solo EDA llamado EDA_homicidios.ipynb el cual contiene las transformaciones(nulos, duplicados, creación de nuevas columnas, cambios de formato de las columnas, manejo de datos faltantes, etc) que se llevo acabo con el fin de analizar el documento y Graficar las distintas situaciones o actores viales involucrados en los accidentes.

- **Panel Interactivo:** Dashboard que facilita la interpretación de la información y el análisis correspondiente se realizo con Power BI el cual se encuentra en la carpeta proyecto bajo el nombre de PI 02 homicidios.pbix.

## Datos Disponibles y KPIs

El dataset abarca información sobre homicidios en incidentes de tráfico ocurridos en CABA durante el periodo mencionado 2016-2021 y del cual se extrajo la información para crear los reportes por tiempo, por zona geográfica, por edad y por las mismas victimas y sus distintos roles y vehículos en los que se movilizaban. finalmente se realizaron cálculos adicionales para realizar los 3 KPIS solicitados los cuales eran.

Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

Para el cual se nos sugirió usar a formula:
(Número de homicidios en siniestros viales / Población total) * 100,000

Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior

para el cual se nos sugirió usar la formula:
(Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

Y finalmente se nos solicito realizar un KPI a nuestra elección, en mi caso en particular decidí proponer reducir en un 10% la tasa de homicidios en los cruces en el ultimo año, en CABA, respeto al año anterior, esta elección la realice ya que el 75% de los accidentes corren en algún cruce de la ciudad. 

La formula que use para desarrollar este KPI fue:
(Numero de accidentes mortales con victimas en los cruces / total de la población) * 100.000

## Conclusiones

Se debe trabajar arduamente en la población masculina en los rangos de edades de los 20-40 años.

Realizar mas campañas de prevención vial en las comunas 1, 4, 7, 8, 9.

la relación Victima/Acusado de los pasajeros peatones es un dato a considerar, ya que la gente esta cometiendo imprudencias viales al salir o ingresar a las transportes públicos.


*Nota: Este README.md proporciona una visión general del proyecto y sus objetivos.
