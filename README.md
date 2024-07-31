<h1> Register-system </h1>

- State: in pogress...
- Add app.js file to the repositorie
- Add css to index


comandos:
- cd nombreDirectorio/                                (cambiarnos de directorio)
- ls                                                  (ver el contenido del directorio en donde estamos)
- git clone https://test.com                          (clonar un repositorio)
- git log                                             (para ver todos los logs)
- git log --oneline                                   (para ver los logs de forma limpia)
- git log -p                                          (no idea)
- git log --since=1.month.ago --until=1.day.ago       (no idea)
- git log --pretty="format:%h %s"                     (no idea)
- git pull                                            (para verificar si estamos actualizados)

/*IMPORTANTE*/

- git status                                          (Verifica si el repositorio local es igual al remoto, de no ser asi, notifica)
- git add .                                           (Si un archivo es creado de forma local, lo añade)
- git push                                            (Envia los cambios delrepositorio local al remoto)

- git commit -m "Texto del comentario"
- git diff index.html                                 (para ver los cambios en ese archivo en especifico)
- git restore --source "hash-de-version" index.html   (hash de laversion - archivo de la version, esto vuelve a una vesion pasada)

/*Comandos para crear ramificaciones*/

- git branch                                          (Muestra las ramificaciones existentes y tambien en la que estas posicionado)
- git checkout -b desarrollo                          (Para crear una nueva ramificacion)
- git switch main                                     (Para swichearte entre las ramificaciones)
- git merge desarrollo                                (Debes estar posicionado en una rama la cual quieres que cambie, luego apuntas a la rama que quieras)
- git push origin main                                (subir los cambios pero esta vez especificando la rama)