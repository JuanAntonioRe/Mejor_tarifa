# Mejor tarifa

Este proyecto usa los datos de 5 datasets, que son de la empresa de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para poder ajustar el presupuesto de publicidad.

En este proyecto se hace mayor enfásis en el análisis estadístico de datos, en la visualización de los datos y en rechazar o aprobar las hipótesis nula y alternativa.

También se hace uso de funciones para realizar diferentes tareas y evitar repetir código, ya que hay operaciones que se deben realizar en las 5 tablas y las cuales son iguales, por ejmplo, aumentar una columna con la suma de los valores de otras columnas.

Se realiza un anáñisis sobre los datos de cada tabla y se hace uso de `Matplotlib` y de `Seaborn` para poder realizar histogramas y gráficas de caja.

## Diferentes Datasets
Para cada tabla se observa como se realizan los mismos pasos:
* Descripción de los datos: se buscan valores ausentes y duplicados.
* Corregir los datos: Se hacen los cambios necesarios para solucionar los hallazgos en el paso anterior.
* Enriquecer los datos: Se agregan columnas para poder realizar un mejor análisis.

## Union de tablas
Se hace uso de la función `merge()` para juntar diferentes tablas y sea más sencillo realizar un análisis tomando datos de dos o más datasets. De esta manera se estudia el comportamiento de los clientes de la empresa Megaline y responder preguntas como: ¿Cuántas llamdas hacen los usuarios? O, ¿cuántos megas de internet se usan en promedio?

## Hipótesis
Se hace un estudio para probar diferentes hipótesis nulas y alternativas, unas de ellas son:
* Hipótesis nula: los ingresos promedio del plan surf son iguales a los ingresos promedio del plan ultimate.

* Hipótesis alternativa: los ingresos promedio del plan surf son diferentes que los ingresos promedio del plan ultimate.