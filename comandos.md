# GIT


## Primeros pasos

### Creando un repositorio

##### 1. Crear um repostorio en GitHub > https://github.com

##### 2.
 
###### Opcion 1: Copiar localmente el repositorio creado en Github 
	$ git clone _dirección https del repositorio a copiar_

###### Opcion 2: 
###### Crear un directorio local con el mismo nombre del repositorio remoto y luego iniciar el repositorio local
	$ git init

###### Vincular repositorio local con el repositorio remoto
	$ git remote add origin _dirección del repositorio remoto_

##### 3. Indicar que archivo o carperta se va adicionar al repositorio
	$ git add _indicar archivo o directorio_

##### 4. Confirmar los cambios realizados en los archivos o directorios, se tiene que indicar un comentario
	$ git commit -m "Mensaje"

##### 5. Mandar todos nuestros cambios (commits) a Github
	$ git push 

##### 6. Indicar cuenta y clave para actualizar informacion en el GitHub


### Actualizando modificaciones en los repositorios

```bash
# 1. Actualizar repositorio local seun los archivos adicionados o modificados
$ git add _nombre del archivo_

# 2. Confirmar los cambios realizados en el repositorio
$ git commit -m "Mensaje"

# 3. Enviar todos los cambios del repositorio local al remoto
$ git push origin master
```	

## Comandos de ayuda

##### Ayuda a saber como funciona git o alguno de sus comandos
	$ git help

##### Muestra el estado del repositorio
	$ git status

##### Visualiza las conecciones realizadas 
	$ git remote -v

##### Visualizar historico del repositorio
	$ git log


## Adcicionar archivo o directorio

##### Adicionar um arquivo em específico
	$ git add _nombre del archivo o directorio_

##### Adicionar todos los archivos y carpetas
	$ git add .

##### Comitar informando mensagem del archivo en especifico
	$ git commit _nombre del archivo_ -m "indicar mensaje"

## Remover archivo o directorio

##### Remover arquivo del repositorio
	$ git rm _nombre del archivo_

##### Remover carpeta del repositorio
	$ git rm -r _nombre del archivo_

##### Remover archivos solo en el repositorio remoto
	$ git rm --cached _nombre del archivo_





