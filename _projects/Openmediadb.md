---
name: OpenMediaDB
banner_img: https://bulma.io/images/placeholders/480x320.png
github_link: https://github.com/CristoferCD/OpenMediaDB
tags:
    - Kotlin
    - Spring
    - API
fe_inicio: 30-12-2018
fe_fin: Actualidad
---

# OpenMediaDB

OpenMediaDB nace con la idea de crear un servidor de medios similar a [Plex](https://www.plex.tv/) pero de código abierto, exponiendo un API que permita a los usuarios crear clientes que se adapten a sus necesidades concretas.

## Tecnologías

El proyecto está creado con Spring Boot y el lenguaje Kotlin. Se usa maven para la gestión de dependencias y el propio proyecto se divide en múltiple módulos con responsabilidades independientes.

Los datos de la aplicación se guardan en MariaDB a la que se accede desde la aplicación mediante el framework *Exposed* de Jetbrains.

Tanto el servidor como la base de datos disponen de una imagen de docker en [omediaserver](https://hub.docker.com/r/cristofercd/omediaserver) y [omediadb](https://hub.docker.com/r/cristofercd/omediadb), respectivamente. Esto facilita arrancar la aplicación en cualquier entorno y el uso de sistemas de integración continua. En este caso se está usando Github Actions para compilar el proyecto, ejecutar los tests y enviar un informe de cobertura a [Codecov](https://codecov.io).
