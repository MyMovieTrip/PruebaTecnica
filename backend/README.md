## Prueba técnica Backend
La prueba consiste en hacer una app que devuelve información de escenas de películas.

Tecnologías requeridas:
- Node
- Sequelize
- MySQL

La entrega final será presentada como un repositorio público de GitHub y se proporcionará la URL para su revisión. Añadir en el README del proyecto el tiempo estimado dedicado a cada tarea.

Cada punto del siguiente listado se tratará como una rama aparte que se mergeará contra máster.


La lista de tareas es:
1.  Crear estructura para proyecto 
2.  Crear entidad SCENES con los siguintes campos: 
     - film_title 
     - creation_date (automática) 
     - photo_url
     - location (coordinates)
     - description
     - country
     - city
3.  Crear endpoint para añadir elementos a la lista, modificar o eliminar escenas de la BBDD.
4.  Crear endpoints para las siguientes consultas:
     - Escenas ordenadas por proximidad a una localización dada (ascendente y descendente).
     - Escenas ordenadas por fecha de creación (ascendente y descendente).

Deberás comenzar a partir del archivo json que se encuentra en este mismo repositorio.


