# Comando de Git 

* git init - crear el repositorio en la carpeta o directorio actual.

* git status - ver el estatus de los archivos en git.

* git add [Nombre del archivo] - agregar archivos a la zona de preparacion.

* git add .(punto) - Para agregar todos los archivos a la zona de preparacion lo hacemos con el Punto (.). De esta manera incluimos todos los archivos.

* git add -A - Agrega al area de preparacion archivos que ya estemos siguiendo.

* git commit -m [MEnsaje descriptivo del commit] - agregar el archivo al repositorio de manera definitiva junto com un comentario entre comillas.Estos archivos tienen que estar en el area de preparacion.

* git commit -a -m "Comentario desciptivo" - agrega el archivo directamente al repositorio sin pasa por el area de preparacion de archivo. En otras palabras pasa del directorio de trabajo a el repositorio git de manera directa. Para que esto sea posible tenemos que seguir primero los archivos si no, no funcionra.

* git commit --amend - modifica el mensaje del commit mas reciente. tambien se puede utilizar para remplazar el commit mas reciente agregandole archivos adicionales. Estos archivos deben estar en el area de preparacion. al utilizar esta sentencia lo que lograresmos es remplazar tanto los archivos como la descripcion del commit.