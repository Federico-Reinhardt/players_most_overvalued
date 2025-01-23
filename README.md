#Jugadores Sobrevalorados

![mkt](https://github.com/user-attachments/assets/4cf8488d-8b3f-4c77-9ba1-f0708d7d0751)


Este proyecto analiza datos de transferencias de jugadores de fútbol para identificar aquellos casos en los que el valor de transferencia supera significativamente su valor de mercado de mercado. La base de datos utilizada fue extraída del sitio reconocido Transfermarkt y se encuentra almacenada en el archivo Futbol_data.db.

La base de datos incluye las siguientes tablas principales:

players: Información sobre los jugadores.

clubs: Datos de los clubes.

transfer: Detalles de las transferencias.

player_valuations: Historial de valoraciones de mercado.

Objetivo del Proyecto

El objetivo principal es identificar y analizar:

Jugadores sobrevalorados: Aquellos cuyas tarifas de transferencia exceden su valor de mercado estimado.

Patrones en transferencias: Como nacionalidad, edad, posición, y rentabilidad de las transferencias.

El valor de mercado de los jugadores es una estimación realizada por el equipo de Transfermarkt, basado en factores como rendimiento, edad, y popularidad.

Herramientas Utilizadas

Este proyecto utiliza Python y las siguientes bibliotecas:

sqlite3: Para la conexión y consulta de la base de datos SQLite.

pandas: Para la manipulación y análisis de datos.
