# git-course-test
Este es un proyecto de prueba creado con Git

gitHub es un gestor de repositorios, el cual contendra los archivos del proyecto y su historia de modificaciones

GIT tiene 3 estados:

1- WORKING DIRECTORY: Es donde trabajaremos con nuestros archivos
2- STAGING AREA: Es donde estare agreagando los archivos que voy a preparar para el guardado (version 1, version 2, version 3...). "ES UN AREA TEMPORAL"
3- Repository: Es el codigo que va a estar ya en el servidor 


COMANDOS BASICOS:

- git init es como decirle a mi sistema operativo que en mi proyecto voy a empezar a utilizar git PARA CONTROLAR LAS VERSIONES DE MI PROYECTO
- git add es para pasar mis archivos del working directory a stagin area
- "git add ." añade todos los archivos que salen en git status sin agregar, esto se hace así para evitar tener que escribir archivo por archivo con el comando add
- git status es para ver en que estado están mis archivos, sea en working directory o incluso en staging area. basicamente uestra los que aun no se an añadido o ya habian sido añadidos pero como han sido modificados hay que guardarlos nuevamente
- git commit es para pasar el archivo del staging area al repositorio (CREA UN SNAPSHOT del codigo de staging area)
- git push es para subirlo a un repositorio remoto (cuando el código se va  a suvir a un servidor, es para que los otros desarrolladores puedan acceder a este)
- git pull trae los cambios que han hecho otros desarrolladores 
- git clone (ruta de mi repositorio de github)    me crea una copia del codigo que está en el servidor para yo poder trabajarlo en mi pc
- git log es para ver el album de "fotos" (fotos que representan a como estaba mi codigo cuando se hizo cada commit, estas fotos tambien traen informacion adicional para poder saber quien la tomo (quien hizo el commit) y la fecha en que lo hizo )
- git commit -m "mensaje que quiero dejar como comentario)", se hace un commit
- .gitignore es un archivo que se crea en el editor, en este listaremos los archivos que desearemos ignorar
- git branch muestra las ramas que hay, si se quiere crear una nueva rama o "nueva version de mi proyecto", se escribe git branch (nombre de la nueva version)
- si quiero cambiar de la "rama" en la que estoy escribo "git checkout (nombre de la rama en la que quiero posicionarme)"



- git diff (nombre archivo) sirve para ver las diferencias hechas en los archivos ¿antes de git add?

- git checkout -- (nombre del archivo) -> git checkout -- index.html     este comando sirve para reversar cambios en el working area cuando he alterado alguno de los archivos






BLUEWEB

git commit lo envia a un repositorio local
- git init solo se hace una vez y es para indicar que esta carpeta utilizara git, esto es para hacerle "seguimiento a la carpeta (proyecto) para saber si ha habido cambios

- git status -s es par mostrar solo que archivos han sido modificados, eliminados o agregados ¿es lo mismo que sin -s?
- git add es para indicar a que archivos les haremos "seguimiento"
- los commit son los que nos sirven "para viajar en el tiempo" (son la foto que le tomamos al codigo)
- git log --online nos trae los comit hechos pero de una forma mas simplificada
- git reset --hard (agregamos el codigo del commit al que queremos volver)    nos lleva a una version de mi proyecto



¿git push para que es?

git push sirve para ingresar los cambios en mi repositoryo al repositorio en la nube (ejemplo: a github)
git pull es para traer el repositorio que hay en la nube a mi working directory

NOTA: Hay cambios en el repositorio (el proyecto) que a veces se hacen directamente en la nube, ejemplo al modificar el archivo README desde github



