# Mi personalizada dmenu
Unas ligeras modificaciones y añadiduras a [dmenu](https://tools.suckless.org/dmenu) para hacerlo más de mi agrado al incluir las funcionalidades esenciales y mantener a su vez su característica simplicidad.

## Montaje
Bajarse el repositorio:

`git clone git@github.com:pablofs02/dmenu`

Acceder al repositorio:

`cd dmenu`

Compilar el programa (se requiere de un compilador de C):

`sudo make install clean`

## Configuración
Modificar el archivo ***config.def.h*** con las opciones que más guste antes de compilar, borrar ***config.h*** y recompilar.

## Parches añadidos
- **caseinsensitive**                       (no se tiene en cuenta la distinción de mayúsculas y minúsculas)
