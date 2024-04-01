# Laboratorio Modulo 0

DESCRIPCIÓN DE LA PRÁCTICA

- Abrimos la terminal en la ruta donde guardaremos el proyecto, y creamos la carpeta del proyecto con "mkdir" y el nombre del proyecto, lo llamaremos "bootcampsjs-modulo00", y luego navegamos hacia ella con "cd bootcampsjs-modulo00".
- Iniciamos el repositorio con "git init".
- Abrimos nuestro proyecto en visual studio code directamente desde la terminal con "code ." y creamos un fichero README.md.
- Lo añadimos al staging con "add ." y hacemos commit a nuestro repositorio local "git commit -m "Ficheros iniciales".
- Ahora conectaremos el proyecto con github, para ello primero creamos un repositorio github público y copiamos la url.
- Luego haremos un "git remote add origin url". Ya estamos conectados con nuestro repo de github.
- Subimos los cambios con "git push --set-upstream origin master" y comprobamos en github que están los cambios.
- Creamos un nuevo archivo:index.html.
- Lo añadimos al staging con "git add .", hacemos commit de los cambios con "git commit -m "Creando un nuevo archivo" y un push para subirlos a la rama main "git push".
- Creamos la nueva rama con "git branch development" y nos movemos a ella con "git checkout development" y modificamos el archivo anterior.
- Hacemos commit a la nueva de este cambio con "git commit -am "Modificando archivo principal"" y un push con "git push -u origin development".
- Volvemos a la rama master "git checkout master" y hacemos el merge de la rama nueva a la principal con "git merge -m "Mezclando ramas" sin ningún conflicto y un push "git push".
- Para finalizar, modifico el README.md con la descripción de la práctica, y hago commit y push de nuevo.
