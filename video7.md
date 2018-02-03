# Comandos del video numero 7 del curso GIt desde cero ED.


* git checkout -b [nombre de la rama] - Este comando sirve para crear y salta inmediatamente a la rama ya creada. Se recomienda tener el directorio de trabajo limpio 

* git branch -v - Muestra la rama donde estamos posicionados y el mensaje del ultimo commit que realizamos.

* git branch --all - Con estas bandera te permite ver las ramas ocultas de los repositorios en la nueve

* git branch -d [nombre de la rama] - Este comando sirve para eliminar la rama. Solo funcionaria si esa rama esta fusionada con otra rama de lo contrario no funcionara

* git branch -D [nombre de la rama] - Este comando sirve para eliminar la rama sin importar si esta rama a sido fusionada este comando forza la eliminacion de dicha rama. ESTE COMANDO ES PELIGROSO PUES ESTA RAMA Y SUS ARCHIVOS SE PERDERAN PARA SIEMPRE.

* git branch --merged - Con este comando git nos informa que ramas han sido fusionadas a la rama actual.

* git branch --no-merged - Con este comando git nos informa que ramas no han sido fusionadas a la rama actual.

* git show [nombre de la etiqueta / Suma de comprovacion] - Sirve para ver cualquier commit o punto en el tiempo.

* git checkout [nombre de la rama] - Este comando sirve para mavernos entre rama. Es recomendable que antes de movernos nuestro directorio de trabajo este completamente limpio y podamos hacer el salto entre rama.

* git remote add origin [direccion de proyecto] - enlaza tu repositorio git al el repositorio en la nube.