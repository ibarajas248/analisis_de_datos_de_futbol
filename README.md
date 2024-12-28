# Proyecto de Análisis de Datos de Fútbol

Este proyecto tiene como objetivo extraer y analizar estadísticas de fútbol de partidos, goles y otras métricas relevantes. Los datos se almacenan en una base de datos relacional, utilizando tres tablas principales: **partido**, **goles** y **estadísticas**. El análisis busca obtener insights sobre el rendimiento de los jugadores, equipos y la evolución de los partidos.

## Descripción del Proyecto

Este sistema permite extraer estadísticas de partidos de fútbol, realizar análisis de desempeño y generar reportes visuales como gráficos y tablas. El flujo principal del proyecto incluye la extracción de datos de los partidos, el análisis de goles y estadísticas individuales de jugadores y equipos, y la visualización de los resultados.

### Tablas Principales

1. **Partido**
   - Información sobre los partidos, como la fecha, equipos involucrados y el marcador final.

2. **Goles**
   - Información sobre los goles marcados durante el partido, incluyendo el jugador, el minuto en que se marcó y el equipo.

3. **Estadísticas**
   - Estadísticas generales del partido, como el número de faltas, tarjetas, intervenciones del portero, balones recuperados y perdidos, entre otros.

## Requisitos

- Python 3.8 o superior.
- Bibliotecas de Python:
  - `pandas`
  - `matplotlib`
  - `mysql-connector-python`
  - `seaborn`
  
- Base de datos MySQL configurada con las siguientes tablas:
  - `partidos`
  - `goles`
  - `estadisticas`

## Instalación

### Paso 1: Configurar el entorno

1. Asegúrate de tener Python 3.8 o superior instalado.
2. Crea un entorno virtual:
   ```bash
   python -m venv venv
