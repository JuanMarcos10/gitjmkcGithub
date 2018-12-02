¿Qué commando utilizaste en el paso 11? ¿Por qué?
$ git reset --hard HEAD~1 --> Utilizo la opción --hard que es la opción con la que se pierde los cambios".

¿Qué commando o comandos utilizaste en el paso 12? ¿Por qué?
$ git reset --hard <8ca089e> (8ca089e: nombre del commit) --> Lo he utilizado despues del comando $ git reflog, el cual nos da todos los pasos y commit que hemos utilizado.

El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?
$ git merge styled --> No causo conflicto. --> Porque solo seguimos teniendo una rama...

El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?
$ git checkout styled --> $ git branch styled --> $ git merge htmlify --> Hay conflictos, normal, dos modificaciones del mismo fichero en dos ramas diferentes, y con un merge...

El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
$ git checkout master --> $git merge styled --> No --> Por que el fichero git-nuestro.md son los mismos, en las dos ramas ver paso 13.

¿Qué comando o comandos utilizaste en el paso 25?
$ git log --decorate --graph --pretty=oneline

Y para configurarlo de manera global en git, se puede usar este alias:
$ git config --global alias.graph “log --graph --decorate --pretty=oneline”

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
$ git merge --no-ff title --> Desde la rama master

¿Qué comando o comandos utilizaste en el paso 27?
$ git reset HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?
$ git reset HEAD git-nuestro.md --> Para sacarlo del Staging Area.

¿Qué comando o comandos utilizaste en el paso 29?
$ git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?
$ git reset --hard 815d399

¿Qué comando o comandos usaste en el paso 32?
$ git checkout 815d399

¿Qué comando o comandos usaste en el punto 33?
$ git reset HARD 815d399 --> NO ENCUENTRO MI TITULO QUE LE PUSE --> Y ES QUE NO HABIA REALIZADO EL COMMIT DE MI TITULO!!!
--> He vuelto a realizar mi titulo, para poder poner todos los tags.
