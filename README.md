# Sistema de gestión universitaria - UML
![kisspng-staruml-unified-modeling-language-xml-metadata-int-5c2f950cd7cf00 723378481546622220884](https://user-images.githubusercontent.com/83146564/125234344-e93dd180-e2b6-11eb-8d08-3f565d3b16dc.png)


# Ejercicio 📝 
Modelar utilizando un diagrama de clases. 
En una universidad existen diferentes aulas, oficinas y departamentos.

Cada departamento tiene un nombre y contiene varias oficinas.

Cada oficina está compuesta por un staff docente y tiene una cantidad de asientos disponibles (misma para todos y conocida desde tiempo de compilación).

El staff docente está compuesto por un profesor y 1 o más ayudantes.

Tanto las oficinas como los profesores y los ayudantes tienen un número "id" que los identifica.

Cada departamento tiene áreas de investigación (puede llegar a no tener) y, dentro de cada área, 1 o más líneas de investigación.

Luego existen proyectos de investigación, cada proyecto corresponde a exactamente una línea.

Un proyecto tiene un nombre, una descripción y una serie de documentos asociados.

Además, cuenta con un único director profesor y varios otros profesores integrantes.

Un documento es un archivo, al que le asignamos un nombre dentro del sistema.

Luego, a muchas aulas les corresponden muchas materias y viceversa.

Cada materia es dictada por un único staff docente, pero cada staff docente puede estar en más de una materia.

Y, finalmente, cada alumno puede inscribirse en muchas materias (puede no inscribirse a ninguna) y una materia tiene a lo sumo 32 alumnos.
