# Mi personalizado dmenu
Unas ligeras modificaciones y añadiduras a [dmenu](https://tools.suckless.org/dmenu/) para hacerla más de mi agrado al incluir sus funcionalidades esenciales y mantener a su vez su característica simplicidad.

## Montaje
Bajarse el repositorio:

`git clone git@github.com:pablofs02/dmenu`

o

`git clone https://github.com/pablofs02/dmenu`

Acceder al repositorio:

`cd dmenu`

Compilar el programa (se requiere de un compilador de C):

`sudo make install`

## Configuración
Modificar el archivo ***config.def.h*** con las opciones que más le guste antes de compilar.

## Parches añadidos
- **alpha**                       (modificar la transparencia del fondo)
- **border**                      (añade un border alrededor de la ventana)
- **center**                      (centra la ventana en el centro de la pantalla)
- **fuzzy**                       (permite emparejamiento por partes)
- **highlight**                   (colorea las letras coincidentes)
- **caseinsensitive**             (no distingue mayúsculas y minúsculas)
- **grid**                        (se puede colocar como reja)
- **gridnav**                     (mejor movimiento en la reja)
- **password**                    (ocultación para contraseñas)
- **separator**                   (cambia el carácter separador)
