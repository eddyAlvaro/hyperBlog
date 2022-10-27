COmandos:
git config  // Nos permite ver todas las configuraciones de git
git config --list: muestra la lista de configuración de nuestro git
git config --list --show-origin: rutas de acceso a la configuración de git


git init                                // Inicializar el repositorio
git status                              // Me muestra el estado de todos los archivos modificados o recien creados
git add                                 // Nos permite validar la informacion en el stagin(memoria ram).
git commit                              // Nos permite guardar los archivos añadidos en el repositorio local.(por defecto se llama MASTER).
git log nombre_de_archivos.extensión    // histórico de cambios con detalles
git push                                // Envía a otro repositorio remoto lo que estamos haciendo
git pull                                // Traer repositorio remoto
git checkout                            // Traer cambios realizados
git rm --cached archivo.extensión       // Remueve el o los archivos guardados en ram cambiando su estado a antes de usar ("git add").
git show nombre_de_archivo.extension    // Nos muestra el nombre del ultimo commit con sus modificaciones.
git diff (idCommit) (idCommit)          // Nos permite comparar las diferentes versiones de commit.
git checkout                            // Nos permite traer los cambios desde el repositorio master.
git merge                               // Permite unir las ramas que vayamos creando, ya sean de (pruebas//development) o (errores//hotfixin).
Comandos linux:

ls                          // listado de carpetas en donde me encuentro.
pwd                         // ubicación actual
mkdir                       // Crea una nueva carpera
touch archivo.extensión     // Crear archivo vacío
cat archivo.extensión       // Muestra el contenido del archivo
history                     // Historial de comandos utilizados durante esa sesión
rm archivo.extensión        // Eliminación de archivo
"comando" --help            // Muestra ayuda sobre el "comando"
