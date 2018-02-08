# Curso Git desde cero
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos.

# Zonas de Git
1. Directorio de trabajo
2. Área de preparación
3. Directorio Git

# Flujo de trabajo básico en Git
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiéndolos a tu área de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantánea de manera permanente en tu directorio de Git.

# Configurando en  Git

Tras instalar Git en nuestro sistema, antes de empezar a trabajar con él tenemos que realizar una
pequeña configuración inicial.

Solo la tenemos que realizar una vez y los valores que vamos a actualizar los podemos cambiar a
posteriori.

El comando que utilizaremos para realizar la configuración de git es

* git config

a partir de hay podemos hacer configuraciones en tres niveles 

## A nivel de sistema

A nivel de sistema, de tal forma que esos valores se utilizarán para cada usuario y para cada
repositorio en el sistema.

Tenemos que utilizar el parámetro “--system” para que los parámetros usados se almacenen a nivel
de sistema.

Esta información se almacena en el archivo “/etc/gitconfig” si estamos trabajando en sistemas Unix.
Si estamos en un sistema Windows este archivo estará también en “/etc/gitconfig”, pero de forma
relativa a donde hemos instalado Git.

Por ejemplo, si lo hemos instalado en “C:\Program Files (x86)\Git\”, la información se almacena en
el archivo “C:\Program Files (x86)\Git\etc\gitconfig”.


## A nivel de Usuario 

A nivel de usuario, de tal forma que esos valores se utilizarán para todos los repositorios en los que trabaje ese usuario concreto.

Tenemos que utilizar el parámetro “--global” para que los parámetros usados se almacenen a nivel
de usuario.

Esta información se almacena en el archivo “.gitconfig”en el directorio raíz del usuario.
Por ejemplo, si estamos en un sistema Unix y nuestro usuario es “fonteLearn”, el archivo estará en
la ruta “/home/fonteLearn/.gitconfig”.

Tenemos que ejecutar el comando “ls -a” para visualizar ese archivo, ya que empieza con un punto.
Si estamos en un sistema Windows este archivo estará en “C:\Users\Mi usuario”, donde “Mi
usuario” se corresponde con el usuario con el que hemos iniciado la sesión. 

Aqui tenemos algunas configuraciones importantes a tomar en cuenta : 

#### git config --global user.name "John Doe" - Usuario .
#### git config --global user.email johndoe@example.com -Emails.
#### git config --global core.editor nano - Editor por defecto.
#### git config --global diff.tool vimdiff -  Mostrar las diferencias entre dos archivos.
#### git config --global merge.tool vimdiff - Herramienta de resolucion de conflicto entre ramas.
#### git config --list -- Mostar las configuraciones del sistema.
#### git config --global color.ui true - Mostrar colores en la salida y poder notar mejor los cambios.
#### git config --global core.autocrlf true - Recomendado en Window.
#### git config --global core.autocrlf input - Recomendado en Unix.


## A nivel de Proyecto

A nivel de proyecto, de tal forma que esos valores solo se usarán para ese proyecto concreto.
Es el nivel predeterminado, con lo que no tenemos que utilizar ningún parámetro.
Esta información se guarda en el archivo “config” dentro del directorio “.git” que se crea en la raíz
del repositorio, como veremos más adelante.
g
En caso de conflicto en un mismo parámetro, la configuración más prioritaria es a nivel de proyecto
y la menos prioritaria a nivel de sistema.

# Solicitar ayuda en Git

git help "comando"
git "comando" --help
