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

-haciendo esto me salto que un artista tenia la celda de los bpm en blanco la localice y resulto ser que carecia de bpm (no estaba el dato) no que no se habia usado algun bpm que es lo que creia antes de buscarlo.

3.4 ARTISTAS Y GENEROS CON MAS Y MENOS BAILABILIDAD:

-he cogido la columna artista y la de bailabilidad y haciendio un recuento de artistas me salen 2 con la mayor bailibilidad que es 96 y buscandolos, los dos artista con mas bailibilidad son UB40 con su cancion "kingstone town" de reggae fusion y Daft Punk con su cancion "around the world de electro.

-obviamente ya hemos deducido que los generos con mas bailabilidad son reggae fusion y electro, pero hay otros generos que les siguen tambien con bastante bailabilidad que son con 95 detroit hip hop y dutch hip hop, seguido de dutch cabaret, glam rock y reggae con 93.

-los que menos bailabilidad tienen son britpop con 10 y classic soundtrack con 12, seguido de art rock y glam rock con 14.

-los artistas con menos bailabilidad son oasis con su cancion "live forever-remastered", seguido de ennio morricone con su cancion "once upon a time in the west-main them".

3.5 AÑOS Y GENEROS CON MAS ENERGIA:

-juntando las columnas años y genero haciendo un recuento de los años, sacamos la conclusion de que el año con mas energia (100) es el 1986, con la cancion angel of death del compositor slayer con el genero alternative metal , los siguientes años con mas energia (99) son 7 , 2 de ellos de 2004 the killers con su cancion somebody told me y green day con american idiot ambas de modern rock, en 2002 alternative metal, en 1984 funk, en 1987 glam metal y en 1994 y 1997 big beat.

-los que menos energia (3) tienen son el genero adult standards en el año 1969 y el siguiente que menos energia (4) tiene es canadian folk en el año 1971.

3.6 ARTISTAS Y GENEROS CON MAS POPULARIDAD:

-el artista con mas popularidad (100) es Tones And I con su cancion dance monkey con un genero australian pop y del año 2019, el siguiente con mas popularidad es maroon 5 con pop en 2019, los dos siguientes con 95 son billie eilish con electropop en 2019 y mariah carey con dance pop en 1994.

-los artistas con menos popularidad 11 es anouk con dutch indie en 1998, el suiguiente con 12 es BLOf con dutch pop en 2018, con 14 emerson,lake & palmer con album rock en 2010, y con 15 wim sonneveld y rob de nijs en 2015 y 2018 con generos de dutch cabaret y dutch pop. 

3.7 DB MAS Y MENOS USADOS A LO LARGO DE LOS AÑOS Y EN QUE GENEROS:

-el mas utilizado es -7 DB, usado 256 veces y utilizando la formula =MODA.UNO() he llegado a que el año que mas se repite es el 2018 con 13 veces, seguido de 2004,2005, 2007,2009 y 2014 con 8 veces y 1976,2002,2011 y 2012 con 9 veces. el genero mas utilizado con -7 DB es album rock en 44 veces, seguido de dutch pop con 23 veces y dance pop con 16, y el genero menos usado en -7 DB son varios solo 1 vez alternative hip hop, alternative dance, alternative pop, art pop . . . entre otros.

-el menos utilizado es -27 DB solo 1 vez en el año 1986 con el genero dutch pop, seguido de -24 DB en 1983 y 1986 con los generos celtic y funk.


3.8 GENEROS CON MAS Y MENOS DURACION:

-observando el promedio de duracion de los generos el que mas suele durar es finnish metal con 7.4 minutos,  seguidos de italian pop con 6.5 minutos y contemporary vocal jazz con 6,4 minutos.

-los que menos duran son rock and roll con 2.6 minutos, seguido de pop punk, motown y chicago soul con 2.8 minutos, y arkansas country con 3.0 minutos.

3.9 GENEROS Y ARTISTAS CON MEJOR Y PEOR ACUSTICA: 

-el genero con mejor acustica es bow pop, del artista yann tiersen con 99 de acustica , seguido de 5 generos mas con 98 de acustica, los cuales son neo mellow, chamber pop, art pop, album rock y glam rock, cuyos artistas son gary jules, agnes obel, tori amos, fleetwood mac y elton john.

-los generos con peor acustica son 224 con una acustica de 0 de los cuales nombrare a 5 detroit hip hop, alternative metal, irish rock, dance pop y adult standards cuyos artistas son eminem, metallica, U2, beyonce y elvis presley .

4.CREACION DEL DASHBOARD:

4.1 TABLAS DINAMICAS (AGRUPAR Y RESUMIR)

4,2 GRAFICOS DINAMICOS (BARRAS, LINEAS, HISTOGRAMAS)

4.3 FILTROS INTERACTIVOS(SEGMENTACIONES DE DATOS PARA AÑO ARTISTA GENERO,ETC...)

5.CONCLUSION:

AUTOR: David Rull Lopez ... julio de 2025.




