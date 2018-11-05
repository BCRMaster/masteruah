# masteruah

First Repository

+++++++++++++++++++++++++++++++++++++++++++++++
LISTA DE COMANDOS GIT UTILIZADOS (O A UTILIZAR)
+++++++++++++++++++++++++++++++++++++++++++++++

PARA CLONAR EL REPOSITORIO DE GITHUB (SÓLO UNA VEZ):

- git clone https://github.com/susannalles/MinimalEditions.git

PARA SUBIR NUEVOS MATERIALES A GITHUB:

- git init: inicia git al interno de la carpeta
- git add nombre_archivo.txt: añade el documento (o carpeta) en el area de espera ("stage")
- git commit -m "mi primer mensaje de cambios": describe los cambios realizados
- git remote add origin https://github.com/susannalles/MinimalEditions.git: apunta a la dirección donde deseáis subir el nuevo material
- git push -u origin master": subís los cambios al repositorio remote en GitHub por primera vez

PUSH & PULL:

- git add *: añade el documento (o carpeta) en el area de espera ("stage")
- git commit -m "mensaje con los detalles del cambio": describe los cambios realizados
- git push origin master: subís los cambios a GitHub *git push origin [branch]: subís los cambios al repositorio remote en GitHub. Asegurar de escribir el nombre del branch que quieres subir sus cambios y nunca subes al master sin que todos revisamos sus cambios.

SINCRONIZAR NUESTRA COPIA CON EL ORIGINAL:

- git pull: baja los cambios del repositorio remoteo a nuestra copia en local

LA BRÚJULA: 

- git status: señala lo que se ha modificado en la carpeta de trabajo

BRANCHES:

- git branch: Para ver en que branch estas trabajando.
- git branch [name]: Para crear un branch nuevo. Asegurar de usar git checkout para camibar al branch.
- git checkout [branch]: Para cambiar de un branch a otro. Así por ejemplo, si estamos en "master" y queremos cambiarnos a un branch llamado "classwork", haremos 'git checkout classwork'.
- git branch -d [name]: Para quitar un branch. Es posible que git te da un error. Git no te permite quitar un branch que tiene commits no escritos al origin con esta orden. Si estas completamente seguro de que quieres quitar el branch, puedes usar la orden git branch -D [name].
- git checkout -b nombre_branch: para bajar el contenido de un branch
- git pull origin nombre_branch: para actualizar el contenido de un branch (y empezar a trabajar en ese branch).
- git checkout -b nombre_branch: para descargar el contenido de un branch
- git checkout -- file.html: para ignorar los cambios hechos en local (cuando queremos hacer un push)


++++++++++++++++++++++++
TABLA ALUMNOS MASTER UAH
++++++++++++++++++++++++

|         NOMBRE         |                       GITHUB                      |
|------------------------|---------------------------------------------------|
|Sergio Avilés           |https://github.com/sergioaviles                    |
|Albert Porres           |https://github.com/AlbertPorres                    |
|José Molina             |https://github.com/Moliholy                        |
|Jesús Alberto Leal      |https://github.com/lealp22                         |

