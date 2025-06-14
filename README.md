# Análisis de Retrasos en Vuelos – Examen de Análisis de Datos 

Este proyecto fue realizado siendo examen del primer parcial de clase, cuyo objetivo fue aplicar técnicas básicas de análisis de datos usando Python y Pandas.

Trabajé con un dataset proporcionado por el profesor. Este contiene datos de vuelos domésticos en Estados Unidos durante el año 2013, y el reto consistía en identificar posibles factores que influyen en los retrasos en la salida y llegada de los vuelos.

## Sobre el dataset

El archivo `flights.csv` incluye columnas como:

- `DepDelay`: Minutos de retraso al despegar
- `ArrDelay`: Minutos de retraso al aterrizar
- `Carrier`: Código de aerolínea
- `OriginAirportName` / `DestAirportName`: Aeropuertos de origen y destino
- `DayOfWeek`: Día de la semana en el que voló

También agregué una columna nueva llamada `LateDeparture`, que indica si el vuelo salió con más de 15 minutos de retraso, y otra llamada `ArrDelay15` que indica si llegó tarde.

## Qué hice en este análisis

1. **Limpieza de datos**: eliminé valores nulos y datos atípicos extremos.
2. **Estadísticas generales**: calculé promedios de retraso por aerolínea, día de la semana y aeropuerto.
3. **Relaciones**: comparé si los vuelos que salieron tarde también llegaron más tarde.
4. **Rutas problemáticas**: encontré las rutas con más retrasos.
5. **Visualización**: generé gráficos para entender la distribución de los retrasos y cómo varían según condiciones específicas.

## Lo que aprendí

Este proyecto me ayudó a entender cómo trabajar con datos reales, desde como cargar y mostrar un archivo.csv usando pandasy polars (aunque no lo use) hasta cómo limpiar y preparar un dataset, y cómo extraer información útil a partir de estadísticas simples. Además, aprendí a presentar mis resultados de forma clara, tanto con código como con gráficas.


Archivo principal:
- [`Pandas_Flights_Challenge_Exa.ipynb`](./Pandas_Flights_Challenge_Exa.ipynb)

## Autor

Diego Eduardo Hurtado Hernández  
Examen – Análisis de Datos  
Vanguardia Guerrero | 2025
Prof. Ing. Cesar Jaime Montiel Moctezuma
