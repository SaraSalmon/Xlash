# 🦈 Proyecto de Análisis de Datos de Ataques de Tiburón

## Descripción del Proyecto
Este proyecto fue desarrollado como parte del bootcamp de análisis de datos, con el objetivo de analizar una base de datos histórica de ataques de tiburones alrededor del mundo desde los años 1800 hasta la actualidad. Nuestro enfoque principal fue darle un uso comercial a los datos, simulando que somos una empresa de actividades acuáticas contactada por RedBull para organizar un evento extremo de natación con tiburones. A partir de este enfoque, realizamos un análisis para determinar el mejor lugar y época del año para organizar el evento, priorizando la seguridad y la emoción de los participantes.

## Enfoque de Negocio
- **Cliente**: RedBull
- **Objetivo**: Organizar un evento de natación extrema con tiburones en un lugar y temporada adecuados para maximizar la seguridad de los participantes, manteniendo el atractivo del evento.
- **Análisis Realizado**: Evaluación de los ataques de tiburones a lo largo del tiempo y por región geográfica, enfocándonos en identificar:
  - Países con mayor número de ataques de tiburón.
  - Temporada del año con mayor incidencia de ataques.
  - Especies de tiburones más peligrosas (aquellas con mayor probabilidad de ataques fatales).

## Estructura de Datos y Proceso de Limpieza
La base de datos inicial contenía información histórica y mundial de ataques de tiburones. A continuación, se describe el proceso de análisis y transformación de los datos:

1. **Limpieza de Datos**:
   - Eliminación de columnas irrelevantes para el análisis, tales como detalles anecdóticos o sin relación con la ubicación y fecha de los ataques.
   - Manejo de valores nulos y datos inconsistentes, asegurando la integridad y homogeneidad de los registros.
   - Estandarización de la información de fechas, países y especies de tiburones para facilitar el análisis.

2. **Transformación de Datos**:
   - Agrupación de los datos por país, año y temporada (primavera, verano, otoño, invierno).
   - Clasificación de ataques por tipo de interacción (provocados/no provocados) para enfocar el análisis en aquellos incidentes más relevantes para el proyecto.

3. **Visualización de los Datos**:
   - Generación de gráficos y tablas para identificar tendencias de ataques por país y estación del año.
   - Visualización de la evolución temporal de los ataques en las regiones con mayor incidencia.

## Resultados
- **País con mayor número de ataques**: Estados Unidos.
- **Temporada con más ataques**: Verano.
- **Especies de tiburones más peligrosas**: Se identificaron como las más peligrosas las especies que históricamente han tenido mayor incidencia de ataques fatales.

### Recomendación Final
Con base en los resultados obtenidos, sugerimos que el evento de natación extrema con tiburones se realice en Estados Unidos durante la temporada de verano. Esta es la época con mayor actividad de tiburones y, por tanto, ofrecería el entorno ideal para un evento extremo, manteniendo el nivel de seguridad adecuado mediante medidas preventivas.

## Tecnologías Utilizadas
- **Lenguajes de Programación**: Python (pandas, numpy, matplotlib, seaborn)
- **Entorno de Trabajo**: Jupyter Notebook
- **Herramientas de Colaboración**: GitHub para el control de versiones y la colaboración entre miembros del equipo.



   
