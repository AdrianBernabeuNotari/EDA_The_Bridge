![imagen](./img/readme_banner.jpg)

# EDA Steam platform

## Análisis de una muestra del cátalogo de la plataforma Steam con juegos publicados de 1997 a 2019

Vamos a revisar datos de precios, fechas de lanzamiento, tendencias y recepción por parte del público, entre otras cosas, para entender como evoluciona el cátalogo de Steam con el tiempo.

### Estructura del repositorio GitHub

- **data**: carpeta con los dos datasets utilizados para realizar el EDA
- **img**: carpeta con tanto las imágenes de los notebook, como las imágenes y gráficos que aparecen en la presentación
- **presentacion**:
- **Data_retrieve**: Jupyter Notebook con el código para extraer datos de las APIs de Steam y SteamSpy
- **EDA_Steam**: memoria del EDA en Jupyter Notebook con limpieza de datos y visualizaciones

### Descripción del proyecto

El objetivo es analizar los datasets combinados con información sobre la plataforma de Steam para entender ciertas tendencias y responder a varias hipótesis y preguntas:
- ¿Hasta que punto los estudios (desarrolladoras) hacen caso a la situación del mercado a la hora de tomar decisiones?
- El éxito de un juego influye en la cantidad de juegos del mismo género publicados sucesivamente.
- Un mayor precio no conlleva necesariamente una mejor recepción por parte del público.
- El precio medio de los juegos ha subido entre 1997 y 2019
- ¿Cuáles son los géneros que más se combinan a la hora de crear videojuegos?
Para ello en un primer momento nos centraremos en el sector de los Metroidvania, y más adelante expanderemos el tema a los demás géneros

### Datasets

Este cuenta con dos datasets de partida:
- Steam: este dataset contiene información sobre las fechas de lanzamiento de los juegos
- SteamSpy: este contiene información sobre los precios, las cantidad de reseñas positivas y negativas de los juegos y las etiquetas puestas por la comunidad (p. ej. Horror, FPS, Roguelite)

### Librerías

Para poder ejecutar el Jupyter Notebook del EDA, es necesario tener instaladas las siguientes librerías:
- Jupyter
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit learn (sklearn)

### Estructura del notebook

1. Datasets
    - Carga
    - Limpieza
    - Fusión

1. EDA
    - Análisis
    - Hipótesis

### Enlace a la presentación de Canva
https://www.canva.com/design/DAG2msoP0wE/LS4sWCfuRRFNzziT20YD-A/edit?utm_content=DAG2msoP0wE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
