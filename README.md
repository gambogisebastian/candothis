# candothis
test y cosas varias


Git
crear el repo vacío (o no) en github y copiar el enlace html (ver hss)
para hacerlo desde el fichero local https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line

ir al directorio local y en la terminal clonar el repo con
git clone (la url del repo en github)
te crea una carpeta con el nombre del repositorio y con un directorio .git oculto adentro

git remote -v

te muestra la dirección de github del repo que acabas de crear

crear un vínculo con el repo para actualizar el local (si el dueño original es otro, primero hay que hacer un fork, después copiar el url del repo en nuestro perfil)

git remote add upstream (url de repo original en github)

para actualizar desde el original

git pull origin master
