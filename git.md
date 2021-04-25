# COMANDOS INTERESANTES DE GIT

Comandos interesantes para el control de versiones con `git`

- `git status` comando comprobar estado de repositorio git
- `git clone` comando para descargar (clonar) un repositorio git desde una estancia url (servidor remoto)
- `git add` añadir un archivo al area de seguimiento (_stagging area_) (modificado,preparado para commit,)
    - `git add .` añade todos los archivos del directorio actual sin seguimiento l _stagging area_
- `git init` inicializa un repositorio en blanco en un directorio existente
- `git commit` comenta cada nueva actualizacion del proyecto
- `git push` inserta las nuevas actualizaciones despues del commit
    - `git push origin master` sube la rama `master` al repositorio remoto `origin` (ver `git remote` mas abajo)
- `git pull` actualiza los cambios realizados
- `git config` gestiona la configuracion de git. Se puede usar con dos argumentos `--global`, `--local`
    - `git config --global user.email "michel_civic@hotmail.com"` configura el email del usuario para cualquier repositorio (modo global) 
    - `git config --global user.name "Miguel Ángel Álvarez"` configura el nombre de usuario para cualquier repositorio

- `git remote` gestiona los enlaces a repositorios remotos
    - `git remote add origin https://github.com/k1michel/proyecto-radares.git` añadiria como el remoto `origin` el enlace `https://github.com/k1michel/proyecto-radares.git`
    - `git remote show origin` muestra los detalles del remoto origin (tiene que coincidir con el `add` previo)
