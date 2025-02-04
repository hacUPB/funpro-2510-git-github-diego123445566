1. Navegar por el sistema de archivos
Para moverse por los directorios, se utilizan los siguientes comandos básicos:

pwd (print working directory): Muestra la ruta del directorio actual.
Ejemplo: pwd
Resultado: /c/Users/tu usuario

ls (list): Muestra los archivos y carpetas dentro del directorio actual.
Ejemplo: ls
Resultado: Documents Downloads Projects

cd (change directory): Cambia el directorio de trabajo.
Ejemplo:

cd Documents te movería a la carpeta Documents.
cd .. te llevaría al directorio superior (uno atrás en la jerarquía).
cd /c/Users/tu usuario/Projects te lleva directamente a esa ruta.
2. Crear directorios
Puedes crear nuevas carpetas con el siguiente comando:

mkdir (make directory): Crea un nuevo directorio o carpeta.
Ejemplo:
mkdir  crea una carpeta llamada mi carpeta en el directorio actual.
mkdir -p proyecto/archivos crea la carpeta proyecto y dentro de ella, la carpeta archivos (si no existen).
3. Crear archivos
Para crear archivos vacíos o de texto, puedes usar estos comandos:

touch: Crea un archivo vacío.
Ejemplo:

touch archivo.txt crea un archivo vacío con el nombre archivo.txt en el directorio actual.
echo: Permite crear un archivo y agregar texto al mismo.
Ejemplo:

echo "Hola, mundo" > archivo.txt crea un archivo archivo.txt y escribe "Hola, mundo" en él.
echo "Otra línea" >> archivo.txt agrega más texto a archivo.txt sin sobrescribir el contenido anterior.
4. Eliminar directorios y archivos
Cuando ya no necesitas un archivo o directorio, puedes eliminarlos:

rm (remove): Elimina archivos.
Ejemplo:

rm archivo.txt elimina archivo.txt.
rmdir: Elimina directorios vacíos.
Ejemplo:

rmdir elimina mi carpeta, pero solo si está vacía.
rm -r: Elimina directorios no vacíos y su contenido de manera recursiva.
Ejemplo:

rm -r elimina mi carpeta y todo su contenido.  resumen de los comandos más utilizados en Git Bash:
Navegar: pwd, ls, cd
Crear directorios: mkdir
Crear archivos: touch, echo
Eliminar archivos: rm, rmdir, rm -r
