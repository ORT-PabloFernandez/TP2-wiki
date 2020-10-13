### GIT
Control de versiones con git

![](https://git-scm.com/images/logo@2x.png)

En el taller de programación 2 vamos hacer un correcto uso del control de versiones en el codigo, y una forma correcta de intercambiar codigo y trabajar colaborativamente. Para lo cual vamos a usar un herramienta que ya es un estandar en el mercado git.

Una guia rapida:
[git the simple guide](https://rogerdudler.github.io/git-guide/index.html)

### GitHub

![](https://cdn.businessinsider.es/sites/navi.axelspringer.es/public/media/image/2015/03/91973-github.jpg)

[sitio oficial](https://github.com/)

GitHub se ha convertido en una autentica plataforma de desarrollo, se usa mucho para soportar el desarrollo distribuido, ademas que también para implementar integración continua, entrega continua, etc.

### Los comandos mas comunes
>  git init 
Podemos ejecutar ese comando para crear localmente un repositorio con GIT y así utilizar todo el funcionamiento que GIT ofrece.  Basta con estar ubicados dentro de la carpeta donde tenemos nuestro proyecto y ejecutar el comando.  Cuando agreguemos archivos y un commit, se va a crear el branch master por defecto.

>  git remote add [nombre_repo_remoto]

>  git help
Muestra una lista con los comandos más utilizados en GIT.

>  git add + path
Agrega al repositorio los archivos que indiquemos.

>  git add -A o git add .
Agrega al repositorio TODOS los archivos y carpetas que estén en nuestro proyecto, los cuales GIT no está siguiendo.

>  git commit -m "mensaje" + archivos
Hace commit a los archivos que indiquemos, de esta manera quedan guardados nuestras modificaciones. Si no se indican archivos se hace un commit sobre todo. 

>  git checkout -b NombreDeBranch
Crea un nuevo branch y automaticamente GIT se cambia al branch creado, clonando el branch desde donde ejecutamos el comando.

>  git branch
Nos muestra una lista de los branches que existen en nuestro repositorio.

>  git checkout NombreDeBranch
Sirve para moverse entre branches, en este caso vamos al branch que indicamos en el comando.

>  git merge NombreDeBranch
Hace un merge entre dos branches, en este caso la dirección del merge sería entre el branch que indiquemos en el comando, y el branch donde estémos ubicados.

>  git status
Nos indica el estado del repositorio, por ejemplo cuales están modificados, cuales no están siendo seguidos por GIT, entre otras características.

>  git clone URL/name.git NombreProyecto
Clona un proyecto de git en la carpeta NombreProyecto.

>  git push origin NombreDeBranch
Luego de que hicimos un git commit, si estamos trabajando remotamente, este comando va a subir los archivos al repositorio remoto, específicamente al branch que indiquemos.

>  git pull origin NombreDeBranch
Hace una actualización en nuestro branch local, desde un branch remoto que indicamos en el comando.
