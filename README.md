# dashboar  d-excel 
SPOTIFY DASHBOARD-ANALISIS CON EXCEL 
en este proyecto voy a analizar casi 2000 canciones en spotify desde el año 2000 .
utilizare excel para la limpieza de datos, analisis exploratorio y visualizacion interactiva mediante dashboard. 
DATASET - FUENTE : https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset 

1.IMPORTACION Y REVISION INICIAL:

-lo primero que he hecho ha sido traducir al castellano los titulos de las colummnas para ver todo mas claro ( he seleccionado todas las columnas y le he dado a revisar y traducir dentro de excel)

-lo segundo que he hecho y he visto claro es pasar la duracion de segundos a minutos (he creado una columna al lado de la de duracion en la que aparecen ya en minutos y con un solo decimal ,he seleccionado la columna de en la que estaban en segundos y la he dividido entre 60 (60 seg = 1 minut) y dan los minutos que son y he ocultado la otra).

-y lo tercero que he hecho ha sido eliminar las columnas que he visto que no me servian para nada de lo que tengo en mente analizar . 

2.LIMPIEZA DE DATOS:

-primero he comprobado si hay titulos duplicados y hay titulos que se llaman igual pero cantados por artistas diferentes al igual que artistas duplicados pero que cantan canciones diferentes , con lo que no puedo eliminarlos (no son valores duplicados como tal) 
lo he comprobado seleccionando todas las casillas de cada columna y en inicio , formato condicional , reglas para resaltar celdas , valores duplicados he dejado en rojo las celdas de las canciones y en verde la de los artistas para que se vea claramente que hice el proceso de mirarlo para ver si habia algun dato que eliminar.

-no hay ningun valor nulo ni ninguna celda en blanco con lo cual mis datos ya estan listos para proceder a su analisis .

3.ANALISIS EXPLORATORIO:

-he creado una tabla dinamica con todas las columnas para hacer unas comprobaciones, a continuacion detallo cuales han sido .

3.1 GENEROS QUE MAS SE REPITEN:
-la primera ha sido coger la columna de genero y artista para ver que genero se repite mas y el que mas se repite es:
  album rock con 413 artistas, seguido de adult standars con 123. (es decir a lo largo de los años los generos que mas se repiten son album rock y adults standars).

3.2 AÑOS CON MAS VARIEDAD DE GENEROS:
-la siguiente ha sido coger año y genero y en 2008 es donde mas variedad de generos hay con 54 tipos de genero distintos seguidos de 1991 y 2018 con 52, y donde menos variedad de generos hay es en 1956, 1960 y 1961 con 1 solo genero (adults standars).

3.3 BPM MAS UTILIZADOS:
-despues he cogido la columna artista y bpm para comprobar que bpm es el mas utilizado por los artistas y es 125 bpm con 40 artistas, seguido de 127 bpm con 39 artistas.

-haciendo esto me salto que un artista tenia la celda de los bpm en blanco la localice y resulto ser que carecia de bpm,(no estaba el dato) no que no se habia usado algun bpm que es lo que creia antes de buscarlo.

3.4 ARTISTAS Y GENEROS CON MAS BAILABILIDAD:

3.5 AÑOS Y GENEROS CON MAS ENERGIA:

3.6 ARTISTAS Y GENEROS CON MAS POPULARIDAD:

3.7 DB MAS USADOS A LO LARGO DE LOS AÑOS Y EN QUE GENEROS:

3.8 GENEROS CON MAS DURACION:

3.9 GENEROS CON MEJOR ACUSTICA: 



