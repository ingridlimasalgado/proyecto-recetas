# COMANDOS DE CONSOLA
## Crear directorios
## Crea una carpeta donde estés trabajando
    $ mkdir carpeta1 
## Crea varias carpetas
    $ mkdir carpeta2 carpeta3 carpeta4 
## Cambia directorio
    $ cd carpeta+tab (change directory nombre_carpeta+tab para autocompletar)
## ¿Dónde estoy?
    $ pwd (me muestra DÓNDE estoy actualmente)
## Selecciono y creo
    $touch index.html style.css (creo archivos desde consola)
## Limpiar
    clear
## salir del directorio
    cd ..
## Listar directorios
    ls
## ejemplo:
    $ mkdir css js img; touch index.html css/style.css js/main.js

### configuración
    $ git config --global user.name "Ingrid Lima"
    $ git config --global user.email "ingridlimas@hotmail.com"


#  INICIALIZAR UN PROYECTO DE GIT
    git init (es un repositorio de git por proyecto {carpeta o directorio}; y dice Inicializado)

## Estado de los archivos
    git status 
    (Untracked files, reconoce carpetas pero no clase-02 porque está vacía y git no las versiona, ¿qué hago entonces? Creo un archivo en esa carpeta: .gitkeep para que sí me aparezca en git status, una por cada carpeta vacía)

### 1) Working directory
    Es el área de trabajo donde voy creando código e interactúo con mis archivos
### 2) staging area
    Preserva y le dice a git que prepare para sacarle foto

    git add archivo_en_seguimiento ("Changes to be committed:" reconoce el archivo en seguimiento)

    $ git commit -m "Agrego README.md en la carpeta clase-01"
### 3) local repo
    $ git diff clase-01/README.md (Para ver el historial de cambios)

## Para ver información del repositorio:
    git log (te muestra todos los commit, arriba el último)

### Para ver toda mi info:
    git config --global -l
### Más específico
    git config --global --get-regexp user (para ver el usuario)

# Tiene que ser en ese orden: add, commit, status

