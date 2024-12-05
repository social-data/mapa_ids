# Índice de Desarrollo Social de la Ciudad de México #

Este mapa representa el índice de Desarrollo Social (IDS) para cada manzana de la Ciudad de México con habitantes. El índice es
calculado por el Consejo de Evaluación de la Ciudad de México (EVALÚA CDMX). El cálculo se basa en la información del Censo de
Población y vivienda 2020 del Instituto Nacional de Estadística y Geografía (INEGI).

El IDS es una medida que resume ocho indicadores agregados: vivienda, educación, bienes durables, energía, adecuación sanitaría,
telecomunicaciones, salud y seguridad social de las personas y para diferentes desagregaciones geográficas. Seleccioné la 
desagregación por colonia para poder visualizar las desigualdades dentro de las mismas.

El cálculo de este IDS se basa en el método de Necesidades Básicas Insatisfechas (NBI), el cual forma parte del Método de Medición
 Integrada de la Pobreza (MMIP), método oficial adoptado por el Consejo de Evaluación para medir la pobreza en la Ciudad de México.

 Para publicar el mapa se unió la capa vectorial de manzanas de la Ciudad de México creada por el Instituto Electoral de la Ciudad
 de México con un archivo CSV que contenía el IDS en distintos niveles de agregación. La unión se realizó en QGIS; posteriormente
 utilicé el PlugIn qgis2web para convertir toda la información en formato web mediante leaflet. Puedes consultar el resultado en 
 Github Pages con este enlace: https://social-data.github.io/mapa_ids/mapa_ids.html
