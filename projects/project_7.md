# Control de inventario de libros

Este proyecto diseñado para los estudiantes de la célula de Desarrollo de Software de CIRT consiste en el desarrollo de una aplicación web que permita llevar un control de los libros que los estudiantes retiran y entregan
de la biblioteca de la universidad.

[Volver al menú principal](https://github.com/aitbw/cirt_projects)

## Objetivos

Para que esta aplicación sea considerada _production-ready_, la misma debe cumplir con lo siguiente:

1. Los administradores (los encargados de la biblioteca) son los únicos que tienen acceso a la aplicación
2. Podrán iniciar y cerrar sesión
3. Panel donde pueden ver los usuarios que tienen acceso a la plataforma, con la posibilidad de crear nuevos o modificar los ya existentes
4. Dentro de la aplicación se podrán crear, modificar o eliminar estudiantes, en donde se tendrán en cuenta los siguientes datos:
   * Nombre del estudiante
   * Cédula de identidad
   * Número de teléfono
   * Correo electrónico
   * Cohorte
   * Carrera
   * Programa de estudios

5. Los usuarios pueden buscar a los estudiantes por número de cédula
6. Los usuarios podrán visualizar los libros que se encuentran en biblioteca, donde se tendrán en cuenta los siguientes aspectos:
   * Título
   * Autor
   * Año de publicación
   * ISBN
   * Cantidad de paginas
   * Portada (Opcional)
   * Hora y fecha en la que se cargó al sistema
   * Hora y fecha en la que se actualizó
   * Número de copias (Máximo de 3 copias)

8. Los usuarios pueden buscar libros por título, autor o ISBN
9. En el sistema, los administradores podrán generar préstamos de los libros disponibles a los estudiantes, en donde se tendrán en cuenta los siguientes aspectos:
   * Libro que se retiró
   * Estudiante que lo retiró
   * Fecha y hora en la que lo retiró
   * Fecha y hora en la que debe devolverlo
   * Usuario que autorizó el préstamo

10. Estas reservas no pueden ser modificadas ni eliminadas
11. Si el estudiante entrega un libro pasada la fecha de entrega, el mismo no podrá retirar ninguno durante un mes

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

* Diseño _responsive_
* Generar multas cuando un estudiante no entregue un libro a tiempo
* Filtrar estudiantes por carrera, cohorte o programa de estudios
* Los administradores pueden ver toda la información referente a los préstamos
* De igual forma, los usuarios pueden ver todos los estudiantes que no pueden retirar libros
* Visualizar los libros que no tienen copias disponibles en el sistema

## Limitaciones

Ninguna más allá del tiempo establecido para elaborar este proyecto.
