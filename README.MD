0- Información en en dashboard:

    En el dashboard se visualizan informaciones de Demanda y Generacion de Energia Electrica de los años 2017 a 2020 inclusive por Año / Provincia, tambien se puede ver la participacion
    de la demanda por tipo de consumidor y el tipo de fuente de Generación.

1- Librerias necesarias para ejecutar la app:
    Python 3.13.7
    pathlib
    duckdb
    pandas
    dash
    plotly
    io

2- dataset:

    Se utilizan dos dataset publicos de la web https://datos.gob.ar/dataset los mismos se encuentran descargados en la carpeta \dataset.

    Dataset Demanda: http://datos.energia.gob.ar/dataset/2b4dfee6-6fca-4e4d-9611-a12d65cd4aa8/resource/ae008cdf-ed5d-4a85-90ee-5f4c53704e79/download/demanda-ltimos-aos.csv

    Dataset Generación: http://datos.energia.gob.ar/dataset/2b4dfee6-6fca-4e4d-9611-a12d65cd4aa8/resource/7da95282-a903-47f0-b4bc-cd1387a62dd3/download/generacin-ltimos-aos.csv

3- Base de datos:

    Se utiliza base de datos duckdb en la notebook "Tp_visualizacion_BD.ipynb" esta los comandos de conección e importación de los dataset.

4- Notebook:

    Abrir la Notebook Tp_visualizacion_BD.ipynb, y ejecutar secuencialmente las celdas, automaticamente se importaran los dataset a la base de datos y mediante Pandas se trasnformaran 
    los datos en Dataframe con la informaciones necesarias para las visualizaciones de la app.
    Nota: en la Notebook antes de cada celda de código se encuentra una celda de Markdown con las explicaciones pertinentes para crear la visualizacion del dashboard.

