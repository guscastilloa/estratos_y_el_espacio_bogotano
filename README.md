# Información de proyecto "Yo por allá no voy"

Proyecto disponible en el [este StoryMap](https://storymaps.arcgis.com/stories/589b1e79e9b5454fbd1f0534d548d198)

Estudio descriptivo de la relación entre la estratificación inmobiliaria en Bogotá y la oferta de bienes y servicios. Los mapas presentados en este trabajo tienen una densidad de Kernel que se puede replicar mediante los scripts [Scripts](/Scripts/2-kdensity/arcpy_kdensity.py).
 
# Datos
Los datos utilizados fueron [tomados de OpenStreetMap](https://download.geofabrik.de/south-america/colombia.html#) y se pueden descargar en [este enlace](https://download.geofabrik.de/south-america/colombia-latest-free.shp.zip). Se agregaron diferentes puntos de interés utilizando la siguiente categorización:

1. CULTURAL:
    - park
    - museum
    - artwork
    - art_centre

2. EDUCACIÓN:

    - school
    - university
    - college

3. ALIMENTACIÓN:
    - supermarket
    - convenience
    - fast_food
    - greengrocer
    - restaurant

4. SERVICIOS:
    - bank
    - optician
    - doctors
    - beauty_shop
    - atm

5. OCIO:

    - bar
    - mall
    - theatre
    - cinema
    
Estas categorías se crearon a partir de mi propio criterio y con apoyo de las categorías usadas [por OpenStreetMap (pág. 6, secc. 4.2)](https://download.geofabrik.de/osm-data-in-gis-formats-free.pdf).
