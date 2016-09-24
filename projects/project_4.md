# Tienda de música

Este proyecto diseñado para los estudiantes de la célula de Desarrollo de Software de CIRT consiste en la elaboración de un sitio web donde los usuarios podrán adquirir las producciones discográficas
de sus artistas favoritos a través de la búsqueda de un amplio catálogo.

[Volver al menú principal](https://github.com/aitbw/cirt_projects)

## Objetivos

Para que esta aplicación sea considerada _production-ready_, la misma debe cumplir con lo siguiente:

1. Sistema de autenticación completo (registro de usuarios, iniciar/cerrar sesión, restablecer contraseña)
2. Solo los administradores podrán agregar nuevos artistas a la base de datos o modificar/eliminar los ya existentes
3. Cada artista tendrá su página dedicada, en donde se deberá visualizar lo siguiente:
   * Nombre del artista
   * Ciudad y país de origen
   * Año en que se comenzó la carrera musical
   * Géneros musicales
   * Foto
   * Biografía (pequeña)
   * Álbumes disponibles para su compra

4. Solo los administradores podrán agregar nuevos álbumes a la base de datos o modificar/eliminar los ya existentes
5. Cada álbum tendrá su página dedicada, en donde se deberá visualizar lo siguiente:
   * Título del álbum
   * Portada
   * Fecha de publicación
   * Género musical
   * _Tracklist_ (en orden y con la duración de cada canción)

6. Carrito de compras (los usuarios pueden agregar álbumes para su posterior compra, así como también pueden eliminarlos)
7. Compra de los ítems en el carrito
8. Generación de un _invoice_ por cada compra que haga un usuario (+ almacenar dicho _invoice_ dentro de la BDD)
9. La BDD deberá tener información precargada al momento que el primer usuario se registre

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

* Ofrecer múltiples ediciones de un álbum a los usuarios (Edición deluxe, edición internacional, etc.)
* Los usuarios registrados pueden comentar los discos que compren
* Ofrecer a los usuarios pre-venta de álbumes seleccionados
* Diseño _responsive_

## Limitaciones

Ninguna más allá del tiempo establecido para elaborar este proyecto.
