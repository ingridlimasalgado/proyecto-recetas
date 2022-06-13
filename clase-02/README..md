# GITHUB 
    /ingridlimasalgado
Si ponés tu mismo nombre de usuario como nombre de repositorio: se crea tu perfil decorado. 
    .git.io
te crea como un dominio gratuito, para pasarle a cualquier persona, como un hosting de sitio estático (no java por ej)

1. Al inicializar no tick nada, sencillo
2. Te viene con las instrucciones para crearlo ahí, o para subirlo desde nuestro ordenador.
3. http o ssh: https para empezar. 

### Repaso
Cuando pongo add, o cambio archivos, dice "Archivos listos para commitear" entonces DEBO hacerle commit, si le quiero agregar algo antes de commit, aplico los cambios necesarios

Debe haber 1 solo .git  dentro de todo el proyecto

4. pegar la 2da opcion en consola. y
    git remote
    git remote -v
    origin

# Agregar remoto en repo local
    git remote add origin <URL>
5. git push... -u única vez, todo lo que esté en master, se va a subir al origin (esa rama). A partir de ese momento todo lo que suba con git push se va a subir a master (On branch master)

Compara lo que hice en la última foto
    git diff

    (origin/master) aparece cuando pusimos git remote. TIENE QUE APARECER EN LA MISMA LINEA con el head (con git status debe aparecer Your branch is up, sino se pone el push)

    **Ver clase: los status que me podrían aparecer**

Si hice modificaciones que no se guardaron en los commit...
    git add . 10:33

¿Qué pasa si no guardé acá si ya hice el commit?
y si agrego un commit se vería irrelevante, qué hago:
    git commit --amend (con esto arreglo lo que me olvidé)

# Agregar imágenes

    !/[status_archivos](URL){width='200px'g}

Tiene que guardarse hasta acá


