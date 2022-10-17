# Comandos para GIT

## Iiniciar git en una carpeta o proyecto

**Antes de hacer cualquier cosa con git, necesitara ejecutar este comando

`git init`

## Revisar estado de los archivos modificados y/o creados

**Los archivos agregados al _Staging_ estara en verde, los que no, estara en rojo

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


