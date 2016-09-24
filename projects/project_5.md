# Clon de Twitter

Este proyecto diseñado para los estudiantes de la célula de Desarrollo de Software de CIRT consiste en la elaboración de un clon de Twitter en donde los usuarios podrán publicar comentarios para compartirlos con sus seguidores
y seguir otras cuentas de interés.

[Volver al menú principal](https://github.com/aitbw/cirt_projects)

## Objetivos

Para que esta aplicación sea considerada _production-ready_, la misma debe cumplir con lo siguiente:

1. Sistema de autenticación completo (registro de usuarios, iniciar/cerrar sesión, restablecer contraseña)
2. Los atributos a considerar para publicar un comentario serán los siguientes:
   * Autor
   * Comentario (máximo 140 caracteres)
   * Fecha y hora de publicación

3. El usuario debe poder ver cuantos caracteres le restan y será imposible comentar algo mayor a ese límite
4. Los comentarios se pueden eliminar, pero no editar
5. Cada usuario tendrá su perfil, donde se tendrá en consideración los siguientes aspectos:
   * _Username_
   * Nombre del usuario
   * Fecha de nacimiento
   * Foto de perfil
   * Biografía (No mayor a 160 caracteres)
   * Locación
   * Todos los tweets realizados por el usuario (ordenados desde el más reciente al más viejo)
   * Links que permita visualizar a quienes sigue y a sus seguidores

6. Cada usuario tendŕa un _timeline_ donde podrá visualizar tanto los comentarios que hace como los de las personas que sigue (ordenados desde el más reciente al más viejo)
7. Se puede responder directamente a un comentario
8. Si un usuario menciona a otro usuario, este último recibe una notificación que le aparece en un panel de notificaciones

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

* Hacer _retweets_ y dar _likes_ a los comentarios
* Envío de mensajes privados entre 2 usuarios
* Diseño _responsive_
* Agregar imagenes a los comentarios

## Limitaciones

Ninguna más allá del tiempo establecido para elaborar este proyecto.
