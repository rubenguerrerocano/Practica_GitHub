# Practica_GitHub
Repositorio para la entrega de las prácticas de GitHub

*- ¿Qué comando utilizaste en el paso 11? ¿Por qué?*
$ git reset --hard HEAD~1, ya que quiero retroceder un commit (HEAD~1) pero además quiero perder los cambios (--hard)

*- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?*
Bueno aquí la he liado un poco creo, pero he hecho un reflog para buscar el commit borrado, he hecho un checkout a ese commit, he creado una branch para no perder el commit y luego he cambiado a styled y he hecho un merge con la nueva branch y he borrado la nueva branch porque no la necesito

*- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?*
Si lo he entendido bien y es estar en styled y hacer un git merge main, no genera conflictos porque styled contiene lo mismo que main, además del cambio del segundo commit, por lo que se queda igual

*- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?*
Si genera conflicto porque el fichero tiene modificaciones diferentes, por tanto git no sabe con cual quedarse

*- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?*
No hay conflicto porque en la rama main no había ninguna bifurcación, por lo que al hacer el merge absorve todos los commits

*- ¿Qué comando o comandos utilizaste en el paso 25?*
git log --graph --pretty=oneline para que me muestr el grafo y cada commit en una línea

*- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?*
Sí, ya que el origen de title era el commit donde estaba main 

*- ¿Qué comando o comandos utilizaste en el paso 27?*
 git reset HEAD~1, ya que al no ser --hard me permite deshacer este paso

*- ¿Qué comando o comandos utilizaste en el paso 28?*
git restore git_nuestro.md, ya que había diferencia entre el working copy y la stage area (aunque verás que hay más commits porque había entendido que descartar los cambios era no hacer el paso anterior, aunque luego me he dado cuenta que no era así)

*- ¿Qué comando o comandos utilizaste en el paso 29?*
git branch -D title

*- ¿Qué comando o comandos utilizaste en el paso 30?*
Un git reflog para buscar el commit del merge, git checkout a main y un git reset --hard y el hash del commit donde haciamos el merge

*- ¿Qué comando o comandos usaste en el paso 32?*
 git checkout 452bbf99375c6aa7e5761f0f7aa932fd982d473b(commit inicial del rezo)

*- ¿Qué comando o comandos usaste en el punto 33?*
Un git reflog para buscar el commit del merge con title y git checkout 38548b6
