# Comandos del video numero 4 del curso GIt desde cero ED.

* git commit --amend - modifica el mensaje del commit mas reciente. tambien se puede utilizar para remplazar el commit mas reciente agregandole archivos adicionales. Estos archivos deben estar en el area de preparacion. al utilizar esta sentencia lo que lograresmos es remplazar tanto los archivos como la descripcion del commit.

* git reset HEAD "nombre de archivo" - Con este comando sacamos el archivo de la zona de preparacion y lo devolvemos a la zona de trabajo.

* git checkout -- "Nombre de archivo" - Este es un comando peligroso, cualquier cambio que se le halla hecho a los archivos desapareceran, nunca utilize este comando a menos que este completaente seguro de no querer las modificaciones hechas a los archivos. Tambien sirve para moverse entre los diferentes puntos de la historio del repositorio o commit, para hacer este salto se omite los "--" y se agrega el sha-1 del commit al que se quiere hacer el salto.

* git clone "Url del repositorio" [nombrede la carpeta (opcional) ] - se clona un repositorio remoto por ejemplo en github. Se descargara en la carpeta donde se ejecute el comando git clone. Clonarlo con este comando da disponivilidad a toda la linea de tiempo y los commit de todo el proyecto.
