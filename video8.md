# Comandos del video numero 8 del curso Git desde cero ED.

* git remote add origin [direccion de proyecto] - enlaza tu repositorio git al el repositorio en la nube.

* git push -u origin [Nombre de la rama en github] - sube todo tu repositorio en local a el repositorio remoto.

* git clone [url del repositorio] {Nombre de la capeta (opcional)}

## Cambios que son hechos en la nube que no estan en nuestro repositorio.

1- Tenemos que hacer un Fork del proyecto.(Un desarrollador ajeno al proyecto).El fork seria una copia del proyecto en nuestra propia cuenta en la nube de github.

2- Clonamos el repositorio desde nuestra cuenta en github a nuestro repositorios locales

3- Efectuamos los aportes necesarios creando ramas locales y hacemos los respectivos cambios y commit.

4- Hacer push de mis mis cambios a el repositorio remoto

5- Hacemos un push request de la repositorio origen. 


## Traer los cambios de un repositorio remoto a un repositorio local.

* git fetch origin [nombre de la rama] - Sirve para traer cambios de un repositorio remoto a nuestro repositorio local. Despues de traer esos cambios mesclamos los cambios con la rama que deseemos. Para poder enpujar los cambios a nuestro repositorio remoto primero debemos jalar los cambios en remoto y luego podemos subir nuestros cambios locales a los repositorio remoto.

* git push origin --delete [nombre de la rama] - Sirve para eleminar una rama remota.

*git remote --verbose - Con este comando podemos ver los repositorios en tenemos acceso de manera remota













