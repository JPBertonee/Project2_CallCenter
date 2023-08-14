# Proyecto Call Center

## Introducción
El propósito de este proyecto radica en examinar las operaciones llevadas a cabo en el Call Center de una entidad bancaria, con el fin de identificar patrones en el comportamiento de los clientes y así poder ofrecer un mejor servicio, incrementando la efectividad operativa. 

El enfoque se dirige hacia la conceptualización, edificación y presentación de un panel de control que habilite la medición de los niveles de excelencia en servicio, eficacia y rendimiento del Call Center.

Para poder alinear el enfoque con el propósito del estudio se propone estudiar las siguientes variables:

1.	¿Cuál es el nivel de atención de llamadas para los clientes prioritarios? 
2.	¿Damos un mejor servicio que a los clientes normales?
3.	¿Qué volumen de llamadas atendemos? 
4.	¿Hay clientes recurrentes en el uso del servicio?
5.	¿Cuáles son los tipos de servicio más recurrentes?
6.	Distribución de llamadas por mes.
7.	Distribución de llamadas por tipo de servicio.
8.	Tiempos promedio de espera en VRU, en cola y en servicio para el segmento de clientes premium.

## Proceso ETL
Una vez identificadas cada una de las columnas y los datos del dataset, se realizó un proceso ETL para limpiar y mejorar la calidad de la información. Dicho proceso fue realizado en  PowerQuery, herramienta de PowerBI.
1.	Modificamos los nombres de las columnas para mejorar la lectura.
2.	Revisamos si los tipos de datos de cada una de las columnas son correctos. 
3.	En la columna customer_id reemplazamos los valores ‘0’ por ‘Unidentified customer’. Para dicho paso, se creó una columna condicional.
4.	Según la documentación de dataset, en la columna priority, los valores 0 deberían ser 1 por la forma en que se prioriza a los clientes. En este paso, modificamos los valores ‘0’ por ‘1’.
5.	En la columna server modificamos los valores ‘NO_SERVER’ por ‘ NO SERVER

## Previsualización del Dashboard



## Conclusiones

Luego de haber trabajado los datos mediante el proceso ETL y de haber aplicado las herramientas de visualización podemos establecer las siguientes afirmaciones:

-	El nivel de atención del call center es de un 79,5%. De las 444.000 llamadas entrantes en el año 1999, se atendieron aproximadamente 353.000. El resto corresponde a llamadas a las que no se dio servicio. 
-	El nivel de atención para clientes prioritarios es del 84,7%. Por otra parte, para los clientes normales es de un 77,1%. Se puede concluir que se le da un mejor servicio a los clientes prioritarios si solo consideramos la cantidad de llamadas que son atendidas comparándolas con las que no se les da servicio. 
-	La recurrencia de los usuarios es algo que podemos observar en los gráficos y en general predominan las llamadas con servicio. 
-	Los servicios más recurrentes son Actividad Regular (PS) y Actividad por acciones (NE).
-	Si analizamos la distribución de llamadas por mes podemos observar que el mes donde más llamadas se recibieron fue en Agosto y el mes con menos cantidad de llamadas entrantes fue Septiembre. Sin embargo, el nivel de atención de Septiembre fue uno de los más altos del año. Podemos creer que la efectividad de las atenciones está ligada al volumen de llamadas entrantes. Quizás no es suficiente la cantidad de agentes para atender las llamadas entrantes y por eso en los meses con mayor volumen de llamados, disminuye el nivel de atención. 
-	Con respecto a los tiempos de espera, se observa una estabilidad durante todo el año ya que no hay picos grandes en la gráfica. Esto ocurre de igual manera para la espera en cola, en contestador y para el tiempo en servicio. 







