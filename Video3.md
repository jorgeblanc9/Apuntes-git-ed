# Comandos del video numero 3 del curso GIt desde cero ED.

* git commit  - Agregas un mensaje de un commit desde el editor por defecto.

* git commit -a -m "Comentario desciptivo" - agrega el archivo directamente al repositorio sin pasa por el area de preparacion de archivo. En otras palabras pasa del directorio de trabajo a el repositorio git de manera directa. Para que esto sea posible tenemos que seguir primero los archivos si no, no funcionra.

* git rm "archivo" - elimina los archivos de directorio de trabajo y los coloca en el area de preparacion para ser confirmado para su posterios eliminacion. se puede sacar del area de preparacion con la sentencia reset HEAD y devolverlo al arbol de carpetas con la sentencia checkout. Se confirma la eliminacion de archivo con el comando commit se recomienda como en todos los commit que se hace hacer una descripcion explicativa de el commit.

* git mv "archivo inicial" "nuevo nombre del archivo" - renombra un archivo o lo mueve de carpeta o directorio. Una ves renombrado el archivo pasa al area de preparacion donde tienen que ser confirmado con el comando commit para validar el renombramirto o el cambio del directorio del archivo.

* git log -Este comando sirve para ver los commits en el repositorio.

* git log -- oneline - muestra el historial agregado en una sola linea. Se puede utilizar jumto con con --graph.

* git log -- graph - muestra el historial de commit por ramificaciones graficas. Se puede utilizar con --oneline.

* git log -- decorate -  este comando sirve para ver las ramas y las etiquetas que conresponde a cada commit. Ojo para mostrar todos los commit independientemente del punto del tiempo en que estemos utilizaremos la bandera --all.

* git log -[numero de commit] - muestra el numero commit que se especifica.

* git log --before="Año-mes-dia"- muestra el historial de commit "ANTES DE" la fecha indicada se puede combinar con --after.

* git log --after="Año-mes-dia"- muestra el historial de commit "DESPUES" de la fecha indicada se puede combinar con --before.

* git log --pretty=format: parametros de formato - despues de los dos punto ubicados en la sentencia format tomara en cuenta los puntos y comas que se escriban entre la sentencia. Es importante que los parametros esten entre comillas.