![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Proyecto 04: Data visualization
*Borja Teruelo y Patricia Barrantes*

*Data Analytics, Part Time, Barcelona, May 2021*

## Resumen

El objetivo de este proyecto es generar visualización de los datos de un dataset, ya sean datos existentes en la web o adquiridos a través de web scrapping.

---

## Dataset

En este proyecto se han usado los datos extraídos del anterior proyecto de web scrapping en el cual se obtenían las 50 películas más populares de todos los subgéneros existentes en la web. Un total de 11.508 fichas de producciones, de las cuales la gran mayoría son películas.

Para organizar los datos, se ha limpiado el dataset (``pelistop.csv``) y se ha creado una base de datos a través de **DB Browser**, dotándole de la siguiente estructura:

[movies.db](https://ibb.co/wzkwtYF)

Las 7 tablas han sido extraídas a sus correspondientes archivos .csv, todos incluidos en la carpeta ``Data``:

* ``1-pelis.csv``
* ``2-direccion.csv``
* ``3-actores.csv``
* ``4-genero.csv``
* ``5-pelis-direccion.csv``
* ``6-pelis-actores.csv``
* ``7-pelis-genero.csv``

## SQL Queries

En el archivo ``PR04-main.ipynb`` está no solamente el código ejecutado en **Jupyter Notebook** para limpiar y obtener los datos y organizarlos en torno a la base de datos, sino también las queries ejecutadas con **SQL** para obtener fragmentos específicos que facilitarían la visualización en **Tableau**.

Las tablas obtenidas a través de **SQL** también se encuentran en la carpeta ``Data`` y los nombres de los archivos siguen la siguiente nomenclatura:

``SQL-[nombre].csv``

## Preguntas

Las preguntas que queremos responder con la visualización de datos son las que se haría una productora cinematográfica:

* ¿Cuáles son los actores más populares que se deben elegir para producir una nueva película?
* ¿Cuáles son los géneros más rentables?

## Visualización

La visualización con la que hemos respondido estas preguntas se encuentra en el siguiente enlace de **Tableau Public**:

[Filmaffinity](https://public.tableau.com/profile/pbarrantes#!/vizhome/Filmaffinity/Filmaffinity?publish=yes)
