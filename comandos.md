# GIT


## Primeros pasos

##### 1. Crear um repostorio en GitHub > https://github.com

##### 2.
 
###### Opcion 1: Copiar localmente el repositorio creado en Github 
	git clone _dirección https del repositorio a copiar_

###### Opcion 2: 
Crear un directorio local y luego iniciar el repositorio
	git init

Vincular repositorio local con el repositorio remoto
	git remote add origin _dirección del repositorio remoto_

##### 2. Copiar localmente el repositorio creado en Github 
	git clone _dirección https del repositorio a copiar_


##### 3. Indicar que archivo o carperta se va adicionar al repositorio
	git add _indicar archivo o directorio_

##### 4. Confirmar los cambios realizados en los archivos o directorios, se tiene que indicar un comentario
	git commit -m "Mensaje"

##### 5. Mandar todos nuestros cambios (commits) a Github
	git push 

##### 6. Indicar cuenta y clave para actualizar informacion en el GitHub


## Comandos

##### ayuda a saber como funciona git o alguno de sus comandos
	git help

##### Muestra el estado del repositorio
	git status

##### Visualiza las conecciones realizadas 
	git remote -v

##### Visualizar historico del repositorio
	git log


### Adcicionar archivo o directorio

##### Adicionar um arquivo em específico
	git add _nombre del archivo o carpeta_

##### Adicionar todos los archivos y carpetas
	git add .

##### Comitar informando mensagem del archivo en especifico
	git commit _nombre del archivo_ -m "indicar mensaje"


### Remover archivo o directorio

##### Remover arquivo del repositorio
	git rm _nombre del archivo_

##### Remover carpeta del repositorio
	git rm -r _nombre del archivo_






