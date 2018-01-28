# Comandos del video numero 5 del curso GIt desde cero ED.

* git tag - lista todas las etiquetas que ya existen y los hace en orden alfabetico.

* git tag [nombre]  - Existen dos tipos de etiqueta la etiqueta ligera que vendria siendo un apuntador o alias de el hast de commit. Esta sentencia se agrega al commit mas reciente.

* git tag -a [nombre] -m[descripcion] - Las otras etiquetas son las etiquetas comentadas estas se guardan en la base de datos de git como objetos enteros tiene un checksum contiene el nombre del etiquetador, correo electronico y fecha es casi como un commit a demas tiene su respectivo cambio asociado.Esta sentencia se agrega al commit mas reciente.

* git tag [nombre] {hast} - Este comando sirve para agregar una etiqueta ligera a un commit en cualquier punto del tiempo.

* git tag -l "patron" - lista las etiquetas que coincida con el patron especificado.

* git tag -d "nombre-etiqueta" - Elimina la etiqueta especifivada en el comando.

* git show [nombre de la etiqueta / Suma de comprovacion] - Sirve para ver cualquier commit o punto en el tiempo.

