COmandos:
git config  // Nos permite ver todas las configuraciones de git
git config --list: muestra la lista de configuración de nuestro git
git config --list --show-origin: rutas de acceso a la configuración de git

<!-- 
git init                                // Inicializar el repositorio

git status                              // Me muestra el estado de todos los archivos modificados o recien creados

git add                                 // Nos permite validar la informacion en el stagin(memoria ram).

git commit -m                           // Nos permite guardar los archivos añadidos en el repositorio local.(por defecto se llama MASTER).

git commit -am                          // JUnta los comandos add y commit en uno, solo funciona con archivos previamente añadidos a stagin.

git log nombre_de_archivos.extensión    // histórico de cambios con detalles

git push                                // Envía a otro repositorio remoto lo que estamos haciendo

git pull                                // Traer repositorio remoto

git checkout                            // Nos permite traer los cambios desde diferentes versiones.

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
