¿ Qué comandos usaste en el paso 11 ? ¿ Por qué ?
Respuesta: git reset --hard HEAD~1

git reset es un comando que sirve para deshacer los cambios locales en el estado de un repositorio de git

--hard : se usa para que reset destruya los datos

HEAD~1 : para poder volver al ultimo commit

¿ Qué comandos usaste en el paso 12 ? ¿ Por qué ?
Respuesta:

git reset --hard 43a8ad0


use este comando porque modifica el head , el indice de los archivos y el contenido local . El estado del proyecto es equivalente al que se encontraba en el commit al que fue reseteado

reset : para regresar el proyecto al estado anterior

¿ Causó algún conflicto el merge donde styled absorve a master ? ¿Por qué?
Respuesta: No causó conflicto , porque styled ya contiene el trabajo de master

¿ el merge del paso 19 causó conflicto ? ¿ Por qué ?
Respuesta: Si Causó, porque ambas ramas en el archivo git-nuestro.md fueron modificadas en las mismas lineas .

¿ el merge del paso 21 causó conflicto del paso ? ¿ Por qué ?
Respuesta: No causó conflicto. Porque master absorve a styled , styled contiene nuestro trabajo de nuestro repo y lo que hacemos es llevar a master hasta el trabajo actualizado

¿ Qué comando usaste en el paso 25 ?
Respuesta: git log --graph

¿el merge del paso 26 podria ser fast-forward?
Repuesta: Si, porque estamos añadiendo el nuevo trabajo que posee title

¿ Qué comando usaste en el paso 27 ?
Respuesta: git reset HEAD~1

¿ Qué comando usaste en el paso 28? Respuesta: git restore git-nuestro.md

¿ Qué comando usaste en el paso 29?

Respuesta: git branch -D title

¿ Qué comando usaste en el paso 30?
Respuesta : git reset de37c63

¿Qué comando usaste en el paso 32?
Respuesta: git reset 6d5600e0708a478a76502db999aff20cb8e84c5e 

¿ Qué comando usaste en el paso 33?
Respuesta: git reset ec9c2d5
