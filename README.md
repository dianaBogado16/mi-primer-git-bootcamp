# Clase 05- GIT

## para crear un repositorio de git

```sh
git init
```

## ver en que estado estan los archivos y en que area:

```sh
git status
```

## Areas del repositorio de git

3 areas
* Working Directory (WD): Directorio de trabajo donde se van agregando o quitando los archivos durante el desarrollo
* Staging area(SA): (Area de control de cambios. Area temporal/ intermedia)  
* Local repo (LR): (Una caja donde voy a ir teniendo todas las fotos que vaya sacando)

## El estado de los archivos

* untracked: (Archivos que estan en el WD pero GIT no les esta dando seguimiento) 
Git sabe que existen pero no les esta dando seguimiento, no sabe si esta cambiando ese contenido
* unmodified: (Archivos que git ya esta siguiendo y con respecto al WD, no fueron modificados)
* modified: Archivos que se encuentran en el repositorio (Estan siendo seguidos por git) pero 
difieren con lo que se encuentra actualmente en el WD  
* staged (changes to be committed) : Archivos que estan en el area temporal/intermedia

## Agrego al area de confirmacion el archivo/archivos

```sh
git add <nombre-archivo>
si tengo varios archivos:
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add. #Agrega todos los archivos.
lo ideal seria ir agregando archivo por archivo, de a poco   
```
