# TPN-3---Max---min---avg-etc

Listar todos los autores de que sean de Nacionalidad Argentina

SELECT * FROM tabla WHERE pais = 'Italia'

Listar todos los autores que tengan hayan publicado entre 1960 a 1980.

SELECT * FROM autores WHERE anio_publicacion BETWEEN "1960" AND "1980";

Mostrar el promedio de la edad de publicación. (avg).

SELECT AVG(edad_publicacion) AS edad_publicacion FROM autores;


