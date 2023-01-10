mkdir   //Crea carpetas
touch   //Crea un txt
cat     //Muestra el contenido de un archivo
history //Muestra el historial de comandos hechos hasta ese momento
rm      //Elimina un archivo
---Git---
git init        //Provoca cambios atomicos en la BD creando estructura interna de git
git status      //Muestra el estado de mis carpetas y de mi repositorio o de mi proyecto
git add (example: history.txt)          // Trackea un archivo dentro de mi proyecto
git rm  (example: history.txt)          // Cachea un archivo dentro de mi proyecto
git rm  (example: history.txt) --cached // Provoca que el archivo se borra pero permanece en chaché
git commit -m "Primer commit" //Envía nuevos cambios al repositorio y debes dejar un mensaje
git config                           //Muestra todas las configuraciones que tiene git
git config --list                    //Muestra la configuracion por defecto y las cosas que hacen  falta
git config --list --show-origin      //Muestra donde estan las configuraciones guardadas (casos avanzados)
git config --global user.name "Name" // Cambias el username de git
