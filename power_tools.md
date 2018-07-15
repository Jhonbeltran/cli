## Power Tools

### Grep y Find

- `grep -n -r . -e [expresion]`: Busqueda (-n) numero de linea (-r) recursiva con (-e) expresión. _ejemplo_:`grep -r . -e perceptron` busca en un directorio de forma recursiva la aparicion de una determinada expresión
- `grep files/movies.dat -e Comedy`: Busqueda dentro de un archivo de una determianda expresión (-e)
- `grep -v [expresion]`: excluye la expresió n de la busqueda
- `find . -name *.py -type f`: Busqueda de archivos por nombre
- `find . -type d [busqueda]`: Busqueda de directorios

### curl, zip y tar

- `curl https://raw.githubusercontent.com/datasets/airport-codes/master/data/airport-codes.csv > arport-codes.csv`: Para hacer un request a una url y usando `>` par almacenarlo en un archivo
- `curl https://raw.githubusercontent.com/datasets/airport-codes/master/data/airport-codes.csv -o arport-codes.csv`: Para hacer un request a una url y usando `-o` par almacenarlo en un archivo
- `zip [nombre.zip] *.csv`: para crear un zip de todos los csv de un directorio
- `unzip -vl [nombredelzip]`: Para listar el contenido del zip sin descomprimirlo
- `unzip [nombredelzip]`: Para descomprimir
- `tar cfz [nombre.tar.gz] *.csv`: para crear un tar.gz de todos los csv de un directorio
- `tar xfz [nombre.tar.gz]` Para descomprimir
- `cat files/movies.dat | awk -F"::" '{printf("%s\n"),$2}'` usamos `awk` para extraer una sola columna de nuestro archivo
