**Entrega practica 1 . GIT  - Grupo BOOTCAMP WEB V EDICION**
**Alumno : JOAQUIN JIMENEZ SANTIAGO**
**email: joaquin@ofitel.info**

EJERCICIO 1 RESPUESTA 

Paso 11: 
         git reset --hard HEAD~1

         *utilizo hard porque se pide que se pierdan los cambios del working copy*

Paso 12:
        git reflog  - para localizar las acciones ralizadas y copiar el id
        git reset -- hard f27a74c
        *utilizo reset hard para que se repongan los cambios incluido el working copy*

Paso 13:
	git checkout styled  - para posicionarnos en styled
        git branch  - para comprobar que estamos en styled
        git merge master 
        
	*No me aparece errror aparede already update*
        **en este momento se me ha perdido el fichero nano escribiendo el ejercicio jeje**
        bueno pero he aprendido que volviendo a hacer el merge y ahora con el nano guardado 
        si vuelvo a hacer merge, 

           -el fichero git-nuestros.md lo deja con el marcado down en styled 
           -me incorpora el readme.md hasta lo que llevaba guardado 
        *echo de menos algo para ir guardando los cambios** 
  
        *

Paso 19 : "merge de styled que absorbe a html"  como git compara por lineas modificas
           y como le hemos metido marcado html en las mismas lineas 


          abro * nano git-nuestro.md*   y veo las diferencias entonces me quedare  con el contenido de styled
          veo que el nano me muestra como 3 grupos de cambios
              -la version inicial con marcado mark down *
              -la version del contenido con etiquetas html 
              -las lineas que no tenian marcado markdown pero no tienen html
              -aunque es un poco complejo pero se entiende como difiere las lineas
              -ahora queda codigo con marcado down + html no se si sera correcto 

          *Ha causado conflicto porque se han modificado las mismas lineas*

Paso 21 : desde master hacer un merge con styled
           *antes debo subir los cambios del fichero con un commit 
            git checkout master 
            git merge styled 
           *me ha pasado los 2 ficheros  git nuestro + readme con los cambios.
           
           *ha realizado un merge fast foward*

Paso 25 :   git log --graph
            git log --graph --decorate --pretty=oneline

Paso 26 :   git merge --no-f title
	    Respuesta de la consola:  Already up to date  
            ¿Podria ser fast-foward?
             No puede ser fast foward porque tenemos otras ramas como son  htmlify
             Aunque pienso que como las ramas html y styled estaban mergeadas se puede hacer. 

Paso 27 :  deshacer el merge "sin perder los cambios del working copy"
           git reset HEAD cc5d7be    - no utilizo hard para no perder el working copy 

Paso 28 :  git merge --abort

Paso 29 : Eliminar la rama tittle
          git branch -D title

Paso 30 : git reset cc5d7be

Paso 32 : Volver al comit inicial 
          git reflog   "me da el id bb14e61 
   

Paso 33 : Volver al estado final , cuando pusimos titulo al poema
          git ref log  " no encuentro la descripcion pongo titulo cogere otro  df344e1
 

