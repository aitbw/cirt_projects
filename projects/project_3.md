# Clon de Reddit

Este proyecto diseñado para los estudiantes de la célula de Desarrollo de Software de CIRT consiste en la elaboración de un sitio web à-la-Reddit/Hacker News, es decir, una página donde los usuarios pueden agregar URLs de interés
y los mismos puedan tanto puntearlas como comentarlas.

[Volver al menú principal](https://github.com/aitbw/cirt_projects)

## Objetivos

Para que esta aplicación sea considerada _production-ready_, la misma debe cumplir con los siguientes parámetros:

1. Permitir a los usuarios poder crear una cuenta en el servicio y poder iniciar/cerrar sesión
2. Solo los usuarios que estén registrados podrán ejecutar acciones sobre el sitio web
3. Los usuarios registrados podrán agregar links al sitio web, los cuales deberán llevar los siguientes atributos:
   * Título
   * Link
   * Hora y fecha de publicación
   * Autor

4. El autor de una publicación será la única persona en capacidad de borrar dicho link
5. Los links pueden ser comentados y se tendrán en cuenta los siguientes atributos:
   * Autor
   * Hora y fecha de publicación
   * Hora y fecha de edición
   * Comentario

6. Un _feed_ principal que permita visualizar los links agregados recientemente, ordenados por su puntuación (de mayor a menor)
7. Visualizar todos las publicaciones que ha hecho un usuario

## Consideraciones adicionales

Al momento de evaluar el proyecto, se tendrán en cuenta los siguientes aspectos:

* Arquitectura MVC
* Código ordenado y comprensible
* El código sigue los estándares establecidos por la comunidad (Depende del lenguaje que se utilice para su desarrollo)
* Diseño de la interfaz gráfica
* Experiencia del usuario
* Documentación
* Uso de principios KISS y DRY

## Opcionales

Si el estudiante así lo desea, puede implementar alguno de los siguientes puntos, lo cual tendrá peso sobre su calificación final:

* Publicar links por categoría
* Filtros para visualizar solo las publicaciones que le interesen al usuario

## Limitaciones

Ninguna más allá del tiempo establecido para elaborar este proyecto.

## Inspiración

Pueden usar [Reddit](https://www.reddit.com/) y [Hacker News](https://news.ycombinator.com/) como referencia para el desarrollo de su aplicación.
