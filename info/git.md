<!--@author:Erick14911-->
# Git `https://git-scm.com/docs/git#_git_commands`

## Inicializando git 

**Inicializa Git**
`git init`

**Lista los datos de la cuenta**
`git config --global --list`

**Nombre de la cuenta**
`git config --global user.name`

**Email de la cuenta**
`git config --global user.email`

**Borrar nombre de la cuenta**
`git config --global --unset-all user.name`

**Agregar un nombre más a la cuenta**
`git config --global --add user.name`

## Status de Git; add y commit

**Revizar status**
`git status -s`

**llevar cambios al area de test**
`git add .`

**Commit guarda el area de test en el repositorio local**
`git commit -m "v0.10"`

**Muestra todos los commit**
`git log --oneline`

**Regresa a un commit anterior**
`git reset --hard (commit)`

## Ramas

**Crear la Rama**
`git branch "name"`

**Muestra todas las ramas**
`git branch`

**Moverse de rama**
`git checkout name`

**Borrar la rama**
`git branch -d name`

## Enlazar a GitHub

**Agregar la direccion del repositorio**
`git remote add origin url.git`

**Revisar repositorio remoto**
`git remote -v`

**Cambiar url del repositorio**
`git remote set-url origin new-url.git`

**Renombrar la direccion del repositorio**
`git remote rename origin newName`

**Remober la direccion del repositorio**
`git remote rm origin`

## Subir archivo a GitHub **Primera VEZ**

**Subir archivo**
`git push origin master`

**Resolver posibles problemas**

~~~
ssh -vT git@github.com
ssh -T -p 443 git@ssh.github.com
ssh-agent -s
~~~

## Trabajar con el repositorio enlazado

**Descargar Repositorio Remoto**
`git clone url.git`

**Verificar cambios en el repositorio remoto**
`git fetch`

**Descargar modificacines remotas**
`git pull`

**Fusionar Ramas**
`git marge nameBranch`

## Etiquetas

**Crear etiquetas**
`git tag dd-mm-aa -m "mensage"`

**Subir etiquetas a la direccion remota**
`git push --tags`

## Fork

**Copiar repositorio a la propia cuenta**

![Boton Fork]()

## Posibles problemas en Visual Studio Code

**Configuración - Administrador de credenciales - credenciales de windows**
