**Entrega practica 1 . GIT  - Grupo BOOTCAMP WEB V EDICION**
**Alumno : JOAQUIN JIMENEZ SANTIAGO**
**email: joaquin@ofitel.info**

EJERCICIO 1 RESPUESTA 

Paso 11: 
         git reset --hard HEAD~1

         *utilizo hard porque se pide que se pierdan los cambios del working copy*

Paso 12:
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

Paso 20 : desde master hacer un merge con styled
            git checkout master 
   
 
