# Dataframes

# Tarea 1
Analizar información académica, con la finalidad de responder 3 preguntas de negocio.

## Preguntas de negocio

- ¿Cuál es el mejor promedio de cada carrera durante el año?
- ¿Cuál es el Catedrático con mayor cantidad de reprobados en cada asignatura por periodo de cada año?
- ¿Cuál es la Cantidad de reprobados de cada carrera por periodos en el año?

## Estructura del proyecto

- Data sources: Es nuestro almacen de data, aquí se encuentran los CSV y json con data a analizar.
- Data merged: Proceso para hacer la unión (merge) de los dataframes en uno solo
- Data cleaning: Proceso para limpiar la data que fue unida anteriormente. *Quitar columnas innecesarias, ordenar las columnas y renombrar algunas columnas*
- Data analysis: Proceso donde llevamos a cabo nuestro analisis exploratorio de datos. *Para resolver nuestras preguntas de negocio*


# Tarea 2
Hacer un LEFT JOIN para no perder información del dataset original. 

## Estructura Proyecto

- Data sources: Es el almacén de datos, donde se encuentran todos los csv con la data a utilizar.
- Data merge: Proceso principal de la asignación, se hace uso de merge; específicamente *Left Join*, para dos dataframes con información relacionada
- Data concat: Proceso de conversión de la data de un modelo *Uno a Uno* a un modelo *Uno a Muchos*, Proceso realizado en clase. *Se realiza ya con el archivo que contiene el merge realizsdo*
