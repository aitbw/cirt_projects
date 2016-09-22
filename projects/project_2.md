# Reseña de libros

Este proyecto diseñado para los estudiantes de la célula de Desarrollo de Software de CIRT consiste en la elaboración de una aplicación web que permita a los usuarios agregar libros y poder reseñarlos.

[Volver al menú principal](https://github.com/aitbw/cirt_projects)

## Objetivos

Para que esta aplicación sea considerada _production-ready_, la misma debe cumplir con los siguientes parámetros:

1. Un sistema de autenticación completo (registro de usuarios, iniciar/sesión, restablecer contraseña)
2. Los usuarios pueden agregar libros a la aplicación (si no existen) o modificar los ya existentes (a modo de colaboración)
3. Los libros que se agreguen deberán llevar los siguientes atributos:
   * Título
   * Autor
   * Año de publicación
   * ISBN
   * Resumen
   * Portada
   * Hora y fecha en la que se publicó en la página
   * Hora y fecha en la que se actualizó

4. Los libros podrán ser reseñados por N cantidad de usuarios y dichas reseñas deberán llevar los siguientes atributos:
   * Autor
   * Hora y fecha de publicación
   * Hora y fecha de edición
   * Reseña

5. Los usuarios que no estén registrados, solo podrán ver el contenido de la misma, no podrán ejecutar ningún tipo de acción sin antes registrarse
6. La base de datos deberá tener libros precargados al momento que el primer usuario se registre
7. Dos (2) _feeds_ (à-la-Facebook/Twitter) que permitan visualizar los últimos libros añadidos a la aplicación y las últimas reseñas hechas
8. Búsqueda de libros (por autor, título o ISBN)

## Consideraciones adicionales

Al momento de evaluar el proyecto, se tendrán en cuenta los siguientes aspectos:

* Arquitectura MVC
* Código ordenado y comprensible
* El código sigue los estándares establecidos por la comunidad (Depende del lenguaje que se utilice para su desarrollo)
* Diseño de la interfaz gráfica
* Experiencia del usuario
* Documentación
* Uso de principios KISS y DRY
* Diseño _responsive_

## Opcionales

Si el estudiante así lo desea, puede implementar alguno de los siguientes puntos, lo cual tendrá peso sobre su calificación final:

* Llamada al API de Goodreads para mostrar los libros
* Género o géneros que abarca el libro
* Comentarios en las reseñas
* Puntuar los libros y/o las reseñas
* Diseñar un perfil personalizable para los usuarios donde se encuentre la siguiente información:
   * Fecha de nacimiento
   * Foto de perfil
   * Biografía del usuario
   * Sexo
   * Locación
   * Reseñas que ha realizado el usuario

## Limitaciones

Ninguna más allá del tiempo establecido para elaborar este proyecto.

## Inspiración

Pueden usar [Goodreads](https://www.goodreads.com/) y [Letterboxd](http://letterboxd.com/) como referencia para diseñar su aplicación.
