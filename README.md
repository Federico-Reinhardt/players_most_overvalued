#Jugadores Sobrevalorados

![mkt](https://github.com/user-attachments/assets/4cf8488d-8b3f-4c77-9ba1-f0708d7d0751)


Este proyecto analiza datos de transferencias de jugadores de fútbol para identificar aquellos casos en los que el valor de transferencia supera significativamente su valor de mercado de mercado. La base de datos utilizada fue extraída del sitio reconocido Transfermarkt y se encuentra almacenada en el archivo Futbol_data.db.

Transfermarkt calcula el valor de mercado de los jugadores considerando varios factores, como la edad, el rendimiento, el potencial futuro, la demanda, el salario y el marketing. También toma en cuenta el contexto general y la situación del club. 

https://www.transfermarkt.es/definicion-de-valor-de-mercado/thread/forum/407/thread_id/2975

Los valores de mercado de Transfermarkt se basan en el criterio de la comunidad, que evalúa y discute los valores de los jugadores. 

Algunos de los factores que se consideran son: 

La edad del jugador

Su posición

Su rendimiento en el club y en la selección nacional

El nivel de la liga

La reputación del jugador

El potencial de desarrollo del jugador

El valor de marketing del jugador

La demanda del mercado

Las perspectivas de futuro

Los valores de mercado de los jugadores se actualizan dos veces por temporada, generalmente al final de la temporada y durante el mercado de invierno

-----------------------------------------------------------------------

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

![python](https://github.com/user-attachments/assets/7f83fa20-9197-4216-b1af-3ba746de27e6)

Este proyecto utiliza Python y las siguientes bibliotecas:

sqlite3: Para la conexión y consulta de la base de datos SQLite.

pandas: Para la manipulación y análisis de datos.

Conclusiones de analisis:

A nivel internacional, podemos observar que en 2009 el Tottenham (Inglaterra) pago al Sheffield United, 40.000.000 euros por el defensor Kyle Walker de 19 años. Su valor de mercado era de 50.000 euros.

Esto implica que se pago un + % 11700. Hoy en día sabemos que es un jugador muy exitosos. Mayormente estas compras son apuestas por clubes grandes por encontrar la joya.

![kyle](https://github.com/user-attachments/assets/55186ab6-2239-4383-b52d-5b32f5ae10aa)

En Argentina podemos observar que uno de los casos sobrevalorados fue la transferencia de Lucas Alario, en 2015 jugador de Colon de Santa Fe paso a River Plate. El valor de transferencia fue de 2.000.000 euros, cuando su valor de mercado era 50.000 euros.

Esto indica que River Plate pago + % 3900 de su valor de mercado.

![lucas-alario](https://github.com/user-attachments/assets/df699875-9fbc-4866-8ed1-35f575fa143e)

En 2024 el Inter de Milán pago por el jugador Tomás Palacios 6.500.000 euros, procedente de Independiente Rivadavia. Su valor de mercado en 2024 era 50.000 euros. Un + % 1200 adicional a su valor de mercado.

![tomas-palacios-inter-milan-2024-2025-1051818524-1729091395-151561](https://github.com/user-attachments/assets/cff2b343-9f0e-49a9-9e6e-960e663c137a)

Algunas transferencias sobrevaloradas post-mundial fue la de Enzo Fernandez, el Chelsea pago 121.000.000 euros por el mediocampista de 21 años. Su valor de mercado era de 55.000.000 euros. Un valor + % 120.

![1010x567_enzo-fernandez-chelsea-480429-184327](https://github.com/user-attachments/assets/d3da19cf-ce4a-4556-b434-97e3c9b83a23)

