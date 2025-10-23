🍷 Análisis Exploratorio del Mercado del Vino en España. 

Este proyecto tiene como objetivo explorar y analizar un conjunto de datos sobre vinos producidos en España, con el fin de identificar tendencias, patrones y posibles relaciones entre precio, tipo de vino, bodega, región y calificación media. El análisis se ha realizado en Google Sheets, aplicando un proceso completo de limpieza, transformación, tipo de vino, bodega, región y calificación media. 

Principales objetivos del proyecto: 
- Detectar y eliminar duplicados en datos originales.
- Estandarizar nombres de bodegas y regiones para evitar inconsistencias.
- Crear dashboards visuales e interactivos que faciliten la interpretación de los datos.

El conjunto de datos original contenía información sobre vinos producidos en España, incluyendo campos como: Bodega, vino, año, nota, reviews, país, región, precio, tipo, cuerpo y acidez. 

Acciones realizadas: 
- Estandarización de valores: Unificación de nombres de regiones y tipos de vino.
- Validación de rangos: Se revisaron los valores atípicos en las pountuaciones (notas de 0 a 5) y precios para verificar coherencia.
- Conversión de datos: Los valores de precio y nota se transformaron a formato numérico para poder generar métricas y medias por grupo.

El resultado es un dataset limpio, consistente y preparado para el análisis gráfico. 

El dashboard final incluye cuatro visualizaciones principales, generadas a partir de tablas dinámicas: 
- La primera gráfica consiste en la Distribución de vinos por Tipo, donde podemos ver que la mayoría de los vinos en el dataset son Ribera del Duero Red (18,7%) y Rioja red (11,3%), seguidos por otros tintos. Esto refleja que predomina el vino tinto en el mercado español.
- La segunda gráfica contiene el Precio Medio por Región, dónde podemos observar que las regiones con vinos tintos más caros son Ribera del Duero, Priorat y Montilla-Moriles, superando los 1.000 euros. Se observa una alta concentración de precios elevados en zonas reconocidas por su denominación de origen.
- La tercera gráfica incluye la Nota Media por Bodega, donde observamos que las bodegas Vega Sicilia, Pago de Carraovejas y Dominio de Pingus destacan por obtener puntuacuones más altas. Sin embargo, la distribución muestra una gran homogenenidad entre bodegas, con pocas diferencias por debajo de una décima.
- La cuarta gráfica nos muestra la Relación entre Precio y Puntuación dónde se confirma la correlación positiva moderada entre ambas variables: Los vinos con mayot precio tienden a recibir puntuaciones más altas, aunque existen excepciones que indican vinos bien valorados a precios medios.


Por último, en cuanto a la verificación de suposiciones encontramos que: 
- Los vinos más caros obtienen mejores puntuaciones. Esto es parcialmente cierto ya que existe una correlación, pero no absoluta; hay vinos de precio medio con valoraciones excelentes.
- Las bodegas con más reseñas tienden a tener mejores notas. Esto no está confirmado, ya que no se observó relación directa entre volumen de reseñas y calificación media.
- Las regiones más reconocidas presentas precios más altos. Confirmada. Regiones como Ribera del Duero y Priorat concentran vinos premium con precios superiores.


Autores: 
Irene Anguita. 
(https://github.com/irenillax/)
