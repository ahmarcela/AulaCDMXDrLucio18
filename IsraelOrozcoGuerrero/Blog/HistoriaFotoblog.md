﻿##Crear una pagina web que imparta cursos de fotografia


Que se muestren los cursos
Que pueda añadir, cancelar y modificar los cursos.
Que tenga login para poder acceder a recursos exclusivos
Que tenga una galeria de los trabajos hechos por los alumnos

Plantilla para una pagina web
Historia de usuario "Mostrar cursos de fotografia"
Yo como MAESTRO
quiero MOSTRAR MIS CURSOS DE FOTOGRAFIA
para QUE EL USUARIO TENGA CONOCIMIENTO DE LOS CURSOS IMPARTIDOS

Criterio de aceptacion
	El usuario navege a los cursos impartidos
Criterios de Aceptacion
	Dado que el usuario ingresa a la pagina web

Historia de usuario "Login para acceder a recursos exclusivos"

Yo como alumno
quiero acceder 
para usar recursos exclusivos a un curso

Criterio de aceptacion
	El usuario debera poner su nombre de usuario y contraseña para	
	acceder a recursos del curso
Criterio de aceptacion en formato BDD
	
	Dado que el usuario quiere recursos exclusivos
	cuando tome un curso	
	entonces al logearse tenga acceso a los recursos.

Historia de usuario"Mostrar trabajos hechos de los alumnos"

Yo como instructor
quiero subir fotos
para mostrar trabajos realizados en los cursos

Criterio de aceptacion
	El instructor debera logearse y tener permisos para
	poder subir, eliminar y modificar fotos
Criterio de aceptaciòn en formato BDD
	Dado que el instructor quiere subir fotos
	cuando tenga los permisos necesarios
	entonces se subiran, eliminaran o modificaran las fotos.
Otro Cambio