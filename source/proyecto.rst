El proyecto
===========
Descripción General
-------------------
El proyecto consiste en sistematizar los datos para obtener información importante, habrá tres tipos de usuarios que son: Administrador, Artista, Visitante.

**El administrador** tendrá todos los privilegios de la aplicación. Este podrá ingresar, actualizar y borrar contenido de la web. Sus principales funciones serán en dar de alta a los artistas que se registren en la aplicación, programa las capsulas de información sobre las reseñas históricas, moderar los comentarios, crear eventos, poder administrar la información sobre los centros culturales, tener acceso a las estadísticas que proporcione el sistema.

**El artista** tendrá que ser dado de alta por el administrador del sistema y será la persona que se publicara su información creando un perfil para ser visto por los visitantes, podrá crear eventos, calificar y comentar.

**El usuario** visitante podrá acceder a toda la información publica del sitio, podrá ver la información de los artistas dados de alta, contactarse con los perfiles de los que llamen su atención, calificar al perfil del artista, ver los eventos calendarizados, comentar sobre lo que piensa de los eventos.

La aplicación podrá tener la opción de filtrar por categorías de artistas, categorías de eventos, puntuación mas alta, por fechas de eventos, entre otras.



Módulos
-------
* **1. Entradas:** en este módulo servirá para poder ingresar, eliminar o actualizar el contenido que el administrador desee publicar en la aplicación. Además, en este módulo el administrador tendrá 250 caracteres para colocar la descripción de hechos que quiera que el usuario visitante vea sobre los acontecimientos históricos. En este módulo se administran las categorías.
 Puede ver el diagrama de caso de uso :ref:`ref_entrada`

* **2. Multimedia:** este servirá para tener organizadas las carpetas de imágenes, música, documentos, etc.
 Puede ver el diagrama de caso de uso :ref:`ref_multimedia`

* **3. Estadisticas:** aquí podrá elegir los reportes que desee ver, este módulo solo puede ser visto por el administrador como ejemplo: artista más visitado, artista más contactado, artista con menos actividad, los principales eventos, entre otros.
 Puede ver el diagrama de caso de uso :ref:`ref_estadisticas`

* **4. Paginas:** el administrador podrá crear nuevas páginas en donde desee publicar información nueva.
 Puede ver el diagrama de caso de uso :ref:`ref_paginas`

* **5. Comentarios** en este módulo se administrarán todos los comentarios nuevos que sean publicados en cualquier perfil, evento, o entrada de la página.
 Puede ver el diagrama de caso de uso :ref:`ref_comentarios`

* **6.Eventos:** se podrá crear eventos con el nombre, descripción, lugar, fecha, precio y ser calendarizados, así mismo poder modificarlos o eliminarlos.
 Puede ver el diagrama de caso de uso :ref:`ref_eventos`

* **7. Artistas:** este módulo tendrá la lista de los artistas  registrados en el sistemas, así mismo aquí podrá dar de alta a los cuales estén en lista de espera, el artista podrá manejar desde este módulo su perfil, esto quiere decir que si desea modificar información inscrita pues hacerlo aquí.
 Puede ver el diagrama de caso de uso :ref:`ref_artistas`

* **8. Usuario**: Este módulo el administrador podrá crear más cuentas administradoras del sistema, para ser accedida por otros usuarios.
Puede ver el diagrama de caso de uso :ref:`ref_usuarios`
