Primer repositorio para probar Git
Comandos Git

*************************** Por ahora el que más me gusta *************************
https://youtu.be/h2ZzlNVl-nI?si=fzuODD2I5LS72R6m

git touch index.html ( creamos este archivo )
Git config —global user.name tu_nombre
Git config —global user.mail tu _mail
Git init ( inicializamos el proyecto )
Git add nombre_archivo ( lo añadimos para la próxima confirmación )
Git status ( vemos cómo está )
Git rm —catched nombre_fichero ( quita este fichero para la próxima confirmación )
Git commit -m “mensaje” ( para informar sobre la trazabilidad )
Git restore nombre_fichero ( lo que hace es volver al estado anterior )
Git log —oneline ( permite ver lo que hemos hecho simplificado )
Git log —oneline nombre_rama ( vemos simplificadamente la rama )
Git checkout HASH ( nos permite movernos a un estado anterior )
Git switch - ( nos permite deshacer la acción anterior )
Git tag nombre_de_la_etiqueta ( permite volver a un punto nombrando su etiqueta )
Git tag ( visualizamos las etiquetas creadas )
Git tag -d nombre_de_la_etiqueta ( para borrar la etiqueta )


Git checkout -b develop ( No se suele usar la rama master y se crea una para producción )

Git branch ( visualizamos las ramas , la activa está marcada con * )
Git branch -d nombre_rama ( eliminas la rama que no interesa )
Git stash ( añadimos el archivo sin usar Git add, crea una pila para luego volver y continuar ) , en caso de que no esté añadido podemos hacer git stash -u . Cuando volvemos para aplicar los cambios utilizamos Git stash pop código ( por ejemplo git stash pop stash@{0} . 
Git stash list ( para visualizar los estados de stash )

Git cherry-pick HASH ( estando en una rama te llevas los cambios a otra rama )

Git merge nombre_rama_donde están los cambios a integrar en esta otra rama

Git diff HASH1 HASH2 ( visualiza las diferencias entre ambos )
Git restore —staged nombre_fichero ( para deshacer cambios en caso de que ya haya sido añadido con Git add )
Git reset HEAD index.html ( hace un reseteo total del fichero …. )
Git revert HEAD ( cuando hemos hecho Git add y git commit y queremos volver atrás. Abre un editor , para salir :q )
Git add nombre_fichero y luego git commit —amend -m “texto” ( agregar un commit a otro que ya hemos hecho )

Git pull origin rama_a_la_que_te_traes_el_repositorio_remoto

Git fetch ( se trae todas los metadatos del repositorio remoto )
Git push origin nombre_repositorio_local ( subimos cambios al remoto )

El fichero .gitignore sirve para incluir archivos o directorios que no queremos subir al repositorio remoto

Git clone url_de_tu_repo ( para clonarlo en local )



