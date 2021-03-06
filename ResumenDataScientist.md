##PROGRAMAS PRINCIPALES A MANEJAR DURANTE EL CURSO:
1. R: la aplicación fundamental con la que se va a trabajar
- RStudio para presentar resultados, conclusiones, ...
- Los formatos de archivos que usaremos serán:
  - R scripts
  - R markdown
2. Git & Github para compartir datos
3. Terminal para los comandos de Git
4. Ayuda para markdown: https://guides.github.com/features/mastering-markdown/

**OBTENER AYUDA**
1. Búscala tú mismo: un amigo, Google, StackOverflow, foro del curso
2. En R:
- ? antes de la función: por ejemplo: ?rnorm accede al archivo de ayuda
- help.search("rnorm")  busca archivos de ayuda
- args(rnorm)           obtiene los argumentos de esa función
- http://cran.r-project.org/doc/contrib/Short-refcard.pdf
3. Foro:
- Ser lo más concreto posible (versión de sofware, sistema operativo, que quería obtener, que pasos he dado, que es lo que obtuve

**GIT & GITHUB**
1. Git es un espacio local en nuestro ordenador donde se trabaja con archivos desde el terminal. 
   Con un sistema de control de versiones. No es necesario tener cuenta en Github ni sincronizar con él, ...
- ¿se pueden crear archivos con marckdown desde el terminal? o hay que hacerlos en otro programa (Word, Google doc, ...)?
2. GitHub sirve para subirlos a la nube:
- Tener una copia de de seguridad de los docs en Internet, 
- Compartir archivos con otros, trabajarlos conjuntamente, 

![Esquema transito Local <-> Remoto]
(https://github.com/LuisRuizDelFresno/Big-Data-Luis/issues/1)

- Subir cambios en el repositorio local al repositorio remoto:
  - git add -A  le dice al local que haga seguimiento de todos los archivos nuevos y los que hayan cambiado o borrado
  - git commit -m "mensaje"  los pone en uan versión intermedia lista para ser publicada en el remoto
  - git push    los sincroniza con el repositorio remoto

- Bajar cambios dekl remoto al local:
  - git pull
