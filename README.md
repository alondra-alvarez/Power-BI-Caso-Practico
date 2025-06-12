# Power-BI-Caso-Practico
## CONTEXTO
En este repositorio se analiza una base de datos mediante el uso de power bi de un negocio que vende y distribuye diferentes tipos de productos en varios países ,para analizar el comportamiento de las ventas y tomar decisiones basadas en el comportamiento observado del negocio

## OBJETIVO
Los equipos de ventas y dirección comercial necesitan un dashboard interactivo y dinámico que les permita identificar oportunidades clave, analizar el rendimiento por productos, categorias y paises,asi como el comportamiento de los envios y tomar decisiones estratégicas basadas en datos para maximizar los ingresos y mejorar la eficiencia comercial.

## PASOS GENERALES
1. Conexion de datosConectar la fuente de datos OData a power BI seleccionando de ella las tablas utiles para el analisis (categories,products,order_details,orders,employess,customers)  
2. Normalizacion y transformacion de datos mediante power query  
3. Modelado de datos-confirmar la relacion entee tablas  
4. Formato y DAX: Agregar el froamto y tipo de datos adecuados a las columnas,general columnas calculadas para poyar el analisis  
5. Creacion de visuales: Generacion de tarjetas informativas para el dashboard con informacion resumida clave (ventas totales,Total de Clientes,Total de paises en los que tenemos presencia)  
6. Generacion de 4 visuales  
7. top 5  ventas por producto  
8. Comportamiento de ventas por año mes a mes  
9. ventas por pais  
10. Comparativa de envios en tiempo y fuera de tiempo  
11. Hacer el dahboard dinamico: Se agregaron filtros de paises y categorias de producto que se aplican a todps los visuales ,adicional a eso cada visual funciona como un filtro para los demas visuales y se agrego etiqueta por categoria al pasar el cursor por cada pasis en el mapa muestra el detalle de ventas dividido por categoria del producto  
## CONCLUSIONES
- Los envios muestran una buena tendencia a lo largo de los 3 años donde el año de 1997 fue el que obtuvo un menor procentage (93.42) que demuestra excelentes resultados
- Las ventas de este año 1998 comparada con los dos anteriores muestran bastante mejora durante los primeros meses del año a este punton se han vendido 1.27 millones de pesos 
- Estados unidos ($245.58 mil) es el pais con mas ventas seguido de Alemania ($230.28 mil) sin embargo se observa en USA un constante disminucion en los envios en tiempo de 1996 a 1998
