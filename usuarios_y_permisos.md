### Usuarios y Permisos

En esta clase vamos a entender los diferentes permisos que puede tener cada tipo de usuario dentro de una computadora. La administración de usuarios y permisos cambia mucho entre diferentes sistemas operativos, pero lo que veremos en clase es igual para todos.

whoami: te dice cuál es el usuario que está operando en ese momento.

Tipos de permisos:

r–: permiso de lectura
rw-: permiso de lectura y escritura
rwx: permiso de lectura, escritura y ejecución
Los permisos tiene valores numéricos: r = 4, w = 2, x = 1. Entonces para otorgar permisos debemos darle un número que sea la suma de cada una de estas tres letras.

Recuerda que cuando haces ls -l, cuando aparezca el listado, podrás ver al comienzo de cada línea cuáles son los permisos. En primer lugar aparecen los permisos del owner (tú), después los del grupo, y finalmente los de todo el mundo.
