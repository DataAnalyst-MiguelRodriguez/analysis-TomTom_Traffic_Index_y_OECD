Infraestructura de transporte: TomTom Traffic Index y OECD Cities

Análisis de 15 ciudades de 7 países para identificar dónde conviene priorizar la inversión en infraestructura de transporte, cruzando congestión vial con indicadores económicos.

Fuentes de datos
TomTom Traffic Index: congestión vial y tiempo que las personas pierden en sus vehículos.
OECD City Economy: crecimiento económico, población y desempleo de las ciudades.
Herramientas
Python (pandas): limpieza, análisis y correlación
Metodología
Limpieza de ambos datasets.
Unión de la información de tráfico y economía por ciudad.
Análisis descriptivo y detección de outliers.
Análisis de correlación entre congestión y productividad económica.
Hallazgos
Las metrópolis tienden a ser las más congestionadas.
A mayor economía, mayor población y, con ello, mayor índice de desempleo.
Los índices de tráfico tienen una desviación alta y presentan outliers, por lo que es más adecuado usar la mediana que la media.
Recomendaciones
Bogotá, Colombia: ciudad prioritaria para inversión, por ser la que muestra la correlación más significativa entre alta congestión y baja productividad económica.
Santiago de Chile: caso a analizar más a fondo.
Montevideo, Uruguay: destaca por su movilidad eficiente y economía sólida.
Estructura del repositorio
├── data/          # datasets originales y limpios
├── notebooks/     # análisis en Python
└── README.md
Autor

Miguel Angel Rodriguez Vega · LinkedIn
