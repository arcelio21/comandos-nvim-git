# Comandos para GIT

## Configuracion inicial

`git config --global user.name "nombre de usuario"` _Para definir el nombre de usuario que usaremos en git_

`git config --global user.email "correo electronico"` _Para definir el email que usaremos (Es recomendado utilizar el email que tenemos registrado en github)_ 

`git config --global core.autocrlf true` [¿Que es core.autocrlf?](https://docs.github.com/es/get-started/getting-started-with-git/configuring-git-to-handle-line-endings#:~:text=El%20comando%20git%20config%20core,Toma%20un%20solo%20argumento.&text=En%20Windows%2C%20simplemente%20pase%20true%20a%20la%20configuraci%C3%B3n.)

`git config --list` _Para ver todas las configuraciones de git_ 

## Iiniciar git en una carpeta o proyecto

**Antes de hacer cualquier cosa con git, necesitara ejecutar este comando**

`git init`

## Revisar estado de los archivos modificados y/o creados

**Los archivos agregados al _Staging_ estara en verde, los que no, estara en rojo**

[¿Que es Staging area y repositorio?](https://platzi.com/clases/1557-git-github/19946-que-es-el-staging-y-los-repositorios-ciclo-basico-/)

`git status`

## Agregar archivos al Staging Area

`git add .` agrega todos los archivos

`git add 'nombre de archivo'` Agrega un archivo en especifico

## Para guardar los archivos al repositorio local

**Antes de ejecutar este comando debe haber agregados a _Staging_ los archivos que desea guardar al repositorio**

`git commit -m "comentario" `

## Para ver los commits realizados en el proyecto

`git log` _Ver los registro con toda la informacion del commit_

`git log --oneline` _Ver el registro de commit mas resumido (recomendado)_

## Para crear una rama en el repositorio local

> Una rama o branch es una versión del código del proyecto sobre el que estás trabajando. Estas ramas ayudan a

> mantener el orden en el control de versiones y manipular el código de forma segura.

[Ilustracion de ramas en git](https://static.platzi.com/media/user_upload/ramas-branch-en-git-7e72b407-90cc-4b90-8de1-738b155764eb.jpg)

`git branch 'nombre de rama'`

`git branch -b 'nombre de rama'` __Automaticamente te mueve o ubica a la rama recien creada__

## Para moverse entre ramas

`git checkout 'nombre de la rama'`

## Para unir un rama a otra

**Es importante que antes de hacer merge, moverse a la rama por medio del 'checkout', a  donde queremos unir la otra rama que decidiremos**

`git merge 'nombre de la rama que uniremos'` _Tenemos que estar ubicado en la rama a donde se unira la otra rama_


## Para agregar repositorio remoto 

`git remote add 'Nombre que le daremos' 'link de rama remota'`

## Para ver repositorio remotos conectado a al repositorio local

`git remote -v`

## Para Clonar repositorio remote

`git clone 'link del repositorio'`


## Subir todas las ramas de un repositorio local a uno remoto

`git push -u origin --all`

## Subir informacion de la rama local a una rama remota

**Es importante agregar los archivos modificados y hacer commit antes de ejecutar el siguinete comando**

`git push origin 'Nombre de a rama remota'`

## Carga o actualiza la informacion del repositorio remoto en el repositorio local 

**Agregar y hacer commit antes de ejecutar este comando**

`git pull origin 'Nombre de a rama remota'`

## Crear Tags

`git tag -a {nombre del tag} -m {comentario de tag}`

## Eliminar tag 

`git tag -d {nombre del tag}`

## Ver tag descripcion de tag

`git show {nombre del tag}`

## Crear tag de un commit anterior

`git log --oneline` _Para ver id de los commits realizados_

`git tag -a {nombre del tag} {id del commit}`

## Subir tags a github

`git push origin {nombre del tag}`

## Subir todos los tags

`git push origin --tags`

## Moverse entre etiquetas

`git checkout {nombre de tag}`

## Moverse entre etiquetas y crear rama a partir de ella

`git checkout -b {nombre de nueva rama} {nombre del tag}`

## Crear un nuevo commit a partir de un anterior

`git revert {numero de commit}`

## Para crear un commit con otro anterior y borrar los que fueron creados despues

`git reset {numero de commit}` _Para ver numero de commit consulta la seccion de log_
