COmandos:
git config  // Nos permite ver todas las configuraciones de git
git config --list: muestra la lista de configuración de nuestro git
git config --list --show-origin: rutas de acceso a la configuración de git
git config --global user.email "<orreo>"

LLAVE PUBLICA Y PRIVADA

comando para generar una llave publica y privada.
    ssh-keygen -t rsa -b 4096 -C "e.alvaro.arenas@gmail.com"

Comando que nos permite verificar el funcionamiento de las llaves.
    eval $(ssh-agent -s)

Agregar la llave privada a nuestro servidor, sistema.
    ssh-add ~/.ssh/id_rsa


<!-- Forma de crear un alias a un comando que nos muestra la historia de commits de forma grafica.

    alias arbol="git log --all --graph --decorate --oneline" 

-->


<!-- 
git init                                // Inicializar el repositorio

git status                              // Me muestra el estado de todos los archivos modificados o recien creados

git add                                 // Nos permite validar la informacion en el stagin(memoria ram).

git commit -m                           // Nos permite guardar los archivos añadidos en el repositorio local.(por defecto se llama MASTER).

git commit -am                          // JUnta los comandos add y commit en uno, solo funciona con archivos previamente añadidos a stagin.

git log nombre_de_archivos.extensión    // histórico de cambios con detalles

git push origin master                  // Envía al repositorio remoto lo que estamos haciendo en local

git pull                                // Traer repositorio remoto

git checkout                            // Nos permite cambiar entre las ramas que tengamos.

git rm --cached archivo.extensión       // Remueve el o los archivos del stagin y del repo local cambiando su estado a antes de usar ("git add").

git show nombre_de_archivo.extension    // Nos muestra el nombre del ultimo commit con sus modificaciones.

git diff (idCommit) (idCommit)          // Nos permite comparar las diferentes versiones de commit.

git reset                               // Nos permite volver en el tiempo pero ya no podremos regresar a los recientes porque los borra.
    git reset --soft                        // Borramos todos el historial y los registros ed git pero mantendremos los datos que tengamos en stagin.
    git reset --hard                    // BORRA TODOOO, NO RESPETA NADA
    git reset HEAD                      // Permite sacar a los archivos del STAGIN, por si no queremos que estos se añadan al ultimo commit.

git clone URL                           // Permite clonar un proyecto desde un repositorio remoto

git fetch                               // Trae al repositorio local pero no lo copia en los archivos.

git merge                               // Permite unir las ramas que vayamos creando, ya sean de (pruebas//development) o (errores//hotfixin). 

git pull                                // Trae los cambios del remoto al repo local (hace lo que fetch y merge pero en un solo comando).

git branch                              // Nos muestra las ramas y nos dice donde estamos.

git remote add origin <URL del remoto>  // Permite añadir el repositorio remoto al local

git remote -v                           // Nos permite ver la url de nuestro repo remoto.

git remote set-url origin <SSH>         // Nos permite cambiar la direccion del repo remoto.

git tag                                 // Nos muestra los tags creados.

git tag -a <nombreTag> -m "mensaje" <hash>  // Forma de crear un tag.

git show-ref --tag                      // Nos musetra a que commits estan asignados los tags que creemos.

git push origin :refs/tags/<nomberTag>  // Forma de eliminar tags en github.

git clone <URL repo>                    / Nos permite clonar un repositorio publico.

-->
**Los tags son utiles en el sitio web, no lo son mucho en local.
<!-- 
    Solucion cuando no me deja hacer pull del master remoto.

        --git pull origin master --rebase
        git config --global pull.rebase true


https://stackoverflow.com/questions/13106179/fatal-not-possible-to-fast-forward-aborting
 -->

<!-- 

    -Para poder utilizar el comando push en un repositorio remoto clonado, primero necesito permisos.
    -Los permisos me los tiene que dar el dueño del repositorio remoto clonado.
    -Para que me pueda dar permisos, el necesita mi username de github o mi correo de github.
    -En el caso del correo, requiero hacer mi correo publico, pero en el caso de que no queramos hacerlo publico, bastara con el username de git para dar acceso al repositorio.

-->


Comandos linux:

ls                          // listado de carpetas en donde me encuentro.
pwd                         // ubicación actual
mkdir                       // Crea una nueva carpera
touch archivo.extensión     // Crear archivo vacío
cat archivo.extensión       // Muestra el contenido del archivo
history                     // Historial de comandos utilizados durante esa sesión
rm archivo.extensión        // Eliminación de archivo
"comando" --help            // Muestra ayuda sobre el "comando"
