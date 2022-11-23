# git-course-test
Este es un proyecto de prueba creado con Git


GIT tiene 3 estados:

1- WORKING DIRECTORY: Es donde trabajaremos con nuestros archivos
2- STAGING AREA: Es donde estare agreagando los archivos que voy a preparar para el guardado (version 1, version 2, version 3...)
3- Repository: Es el codigo que va a estar ya en el servidor 


COMANDOS BASICOS:

- git init es como decirle a mi sistema operativo que en mi proyecto voy a empezar a utilizar git
- git add es para pasar mis archivos del working directory a stagin area
- git status es para ver en que estado están mis archivos, sea en working directory o incluso en staging area
- git commit es para pasar el archivo del staging area al repositorio
- git push es para subirlo a un repositorio remoto (cuando el código se va  a suvir a un servidor, es para que los otros desarrolladores puedan acceder a este)
- git pull trae los cambios que han hecho otros desarrolladores 
- git clone me crea una copia del codigo que está en el servidor para yo poder trabajarlo en mi pc



- git branch muestra las ramas que hay, si se quiere crear una nueva rama o "nueva version de mi proyecto", se escribe git branch (nombre de la nueva version)

- si quiero cambiar de la "rama" en la que estoy escribo "git checkout (nombre de la rama en la que quiero posicionarme)"

- git status sirve para mostrar el estado de mis archivos, basicamente uestra los que aun no se an añadido o ya habian sido añadidos pero como han sido modificados hay que guardarlos nuevamente,

- "git add ." añade todos los archivos que salen en git status sin agregar, esto se hace así para evitar tener que escribir archivo por archivo con el comando add


- git commit -m "mensaje que quiero dejar como comentario)", se hace un commit

- git log es para ver el album de "fotos" (fotos que representan a como estaba mi codigo cuando se hizo cada commit, estas fotos tambien traen informacion adicional para poder saber quien la tomo (quien hizo el commit) y la fecha en que lo hizo )
