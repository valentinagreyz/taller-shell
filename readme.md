Si estás leyendo este archivo, es que has conseguido clonar de manera correcta el
repositorio.
Cuando indique la persona responsable del taller, comenzará la actividad. Hasta entonces
no hagas nada.
1. ACTUALIZAR REPO
a.
b.
c.
d.
Entra en la carpeta clonada desde terminal (cd).
Baja los contenidos nuevos en la carpeta (git pull).
Busca si hay algún archivo nuevo (ls)git p.
En caso de haberlo, ejecútelo (./helloworld.sh).
2. CREA TU PROPIO REPO
a. Desde la versión web de git, vas a crear tu propio repo (myfirstrepo).
b. Creamos un nuevo remoto:
git remote add destino https://ejemplo.com/mi-nuevo-repositorio.git
c. Crea un archivo llamado README.md usando nano.
d. Añade todos los archivos para enviar a git (git add .)
e. Haz el commit de los archivos (git commit -m “creado readme”).
f. git push -u destino main (subimos a nuestro repo los cambios).
3. CREAR UNA NUEVA CARPETA
a.
b.
c.
d.
Crea una carpeta en el directorio que se llame “ejercicio_2” (mkdir).
Crea un archivo llamado “receta” (touch).
Edita el archivo para incluir alguna de su receta favorita (gedit / nano).
Sube el archivo como hemos indicado arriba.
4. CREA UNA RAMA
a.
b.
c.
d.
e.
Crea una nueva rama que se llame ”no_salt” (git branch no_salt).
Muévete a esa rama (git checkout no_salt).
Añade en la receta una línea al final que ponga “añadir menos sal” (gedit).
Sube el archivo al repo.
Observa los cambios y la rama desde el navegador web.
5. HAZ UN MERGE DE AMBAS RAMAS
a.
b.
c.
d.
Haz un merge de las dos ramas (git merge main no_salt).
Mira las ramas que hay ahora (git branches).
Mira lo que pone en el archivo receta (cat).
Observa y entiende lo que ha pasado (git log - - graph).
6. EJERCICIO LIBRE
a. Trabaja en git creando ramas y archivos, si tienes cualquier duda
consultanos.
