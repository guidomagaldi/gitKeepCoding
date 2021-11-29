¿Qué comando utilizaste en el paso 11? ¿Por qué?  Utilize git reset —hard deb1764, por que debía perder los cambios en el working copy en un solo comando
Primero para obtener el numero de referencia utilice git reflog

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?  
Utilice primero git reflog para ver los logs de todos mis movimientos Y luego con un git reset --hard volvi al commit en donde había modificado el git-nuestro de la rama styled. 
El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 

Al intentar hacer un merge recibo un cartel diciendo :  “Ya está actualizado.” Esto es por que styled es una rama cuyo parent es main y tiene todos los commits del main.
Por lo tanto no se hace el merge.


El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?  
En este punto tenemos un conflicto, por que el contenido de styled y htmlify en su archivo git-nuestro es diferente. Aqui accedemos al archivo git-nuestro.md en styled y nos quedamos con el texto de styled.
Luego hacemos un git add git-nuestro.md y un commit y el conflicto queda resuelto

El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
Sin conflictos, fast forward desde main a styled. 


¿Qué comando o comandos utilizaste en el paso 25?  

Git log —graph

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si podría ser fast forward ya que las ramas forman una lista, Title tiene todos los commits de Master entonces si se podría.


¿Qué comando o comandos utilizaste en el paso 27? 
He utilizado git reset y el numero de identificación que he adquirido del git reflog.


¿Qué comando o comandos utilizaste en el paso 28? 
Git add . Y git commit -m”” para terminar de descartar los cambios

¿Qué comando o comandos utilizaste en el paso 29? 
 Git branch -d “title”

¿Qué comando o comandos utilizaste en el paso 30? 
Git reflog para ver el identificador de donde estaba title
Git checkout para ir hacia ahi Git branch title para hacer la rama de nuevo
Git checkout title para mover head a title

¿Qué comando o comandos usaste en el paso 32? 
Git log y podemos ver los commits de main
Y con git reset —hard puedo ir al primer commit que fue cuando se creo el poema

¿Qué comando o comandos usaste en el punto 33?
Git reflog para ver cuando le puse titulo al poema.
Git reset —hard para ir allí con el numero de identificación 

 

 
 
 
