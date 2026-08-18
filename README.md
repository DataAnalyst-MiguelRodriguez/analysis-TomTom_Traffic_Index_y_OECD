El objetivo es evaluar cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades latinoamericanas. Se trabajará con datos de TomTom Traffic Index y OECD Cities, que se limpiaran, combinaran y analizaran para identificar en qué ciudades conviene invertir en infraestructura de transporte.


Paso 1: Cargar y explorar
Antes de limpiar o combinar los datos, es necesario familiarizarte con la estructura de ambos datasets. En esta etapa, validarás que los archivos se carguen correctamente, conocerás sus columnas y tipos de datos, y detectarás posibles inconsistencias.
________________________________________
Paso 2: Explorar, limpiar y preparar los datos
Antes de combinar los datasets, inspecciona su estructura, tipos de datos, columnas y valores faltantes. Anota las columnas que necesiten limpieza y luego estandariza los nombres de columnas.
2.2 Renombrar columnas
🎯Objetivo: Estandarizar los nombres de columnas para evitar errores y facilitar la unión de los datasets.
2.3 Corregir formatos numéricos y de fecha
🎯Objetivo: Asegurar que las columnas de fechas y valores numéricos estén en formatos correctos para permitir análisis, cálculos y comparaciones precisas.
Haz clic para ver la pista para eliminar símbolos, puedes reemplazarlos por un texto vacío.
________________________________________
Paso 3: Extraer año y filtrar
Extraer el año permite filtrar la información y trabajar solo con el período más reciente y relevante.
3.1 Extraer columna año y filtrar 2024
🎯Objetivo Identificar el año de cada registro y mantener solo los registros del 2024.
________________________________________
Paso 4: Analizar y resumir datos de movilidad
Como el dataset de tráfico contiene múltiples registros por ciudad. En esta parte, calcularás los promedios anuales por ciudad para simplificar el análisis y obtener una visión más clara de las tendencias generales.
4.1 Calcular promedios de tráfico por ciudad
🎯Objetivo: Obtener una vista consolidada del tráfico promedio por ciudad y año, para analizar patrones generales sin depender de datos diarios.
________________________________________
Paso 5: Unir movilidad y economía
Combinar datasets te permite analizar cómo se relacionan los indicadores económicos con los de movilidad.
5.1 Unir tráfico (tabla principal) con indicadores económicos
🎯Objetivo: Combinar la información de tráfico y economía en un solo DataFrame para analizar cómo las condiciones económicas se relacionan con la movilidad urbana.
________________________________________
Paso 6: Visualización y análisis de relaciones
Ahora que tienes un dataset limpio y unificado, es momento de visualizar patrones. Los gráficos te ayudarán a entender cómo se relacionan las variables económicas con las de movilidad urbana.
6.1 Visualizar relaciones entre economía y tráfico
🎯Objetivo: Analizar visualmente la distribución y la relación entre indicadores de tráfico y economía en 2024, para identificar posibles patrones o tendencias generales entre ambas variables.

________________________________________
Paso 7: Documentar resultados
7.1 Guardar dataset final
🎯Objetivo: Generar un CSV limpio, reproducible y con columnas relevantes para análisis posterior.
