# Instreuctivo

## Etiquetas

**\<section>\</section>**: Esta es la etiqueta para definir seciones o separar seciones de la pagina web.

## GIT

### Configuración git 

- git config --global user.name "John Doe"
- git config --global user.email johndoe@example.com

### Enlazamiento con la repo
- Para inicializar un proyecto usamos **git init**.
- Para cambiar la rama principal usamos **git branch -M \<nombre rama main>**.
- Para crear una nueva rama usamos **git branch \<nombre rama>**.
- Para cambiar de rama usamos **git checkout \<nombra rama>**
- Para obtener lista de ramas y saber en que rama estamos usamos **git branch -v**.
- Para generar una conexión con nuestro repositorio usamos **git remote add \<nombre del enlace a la repo. ej. origin> "\<direcion del repositorio>"**.
- Para listar las conexiones que tenemos de repositorios usamos **git remote -v**
- Para eliminar enlace con al repo usamos **git remote remove \<nombre del enlace>**.

### Informacion para adicion y publicacion de cambios dentro de la repo

- Para agregar cambios realizados en los archivos usamos **git add \<nombre del archivo o ruta del archivo con el archivo o solo ruta del directorio.>** o **git add .** (Con esta ultima agrega todos los cambios).
- Para crear el commit se hace **git commit -m "\<Mensaje del commit>"**.
- Para subir los cambios usamos **git push \<nombre del enlace, ej. origin> \<nombre de la rama donde se va a publicar>**.
- Para traer cambios que hayan subida a la repo otros compañeros a la rama que se esta trabajando usamos **git pull \<nombre del enlace, ej. origin> \<nombre de la rama que se quiere enviar los cambios>**.
- Para revisar algun cambio que haya en la repo o en nuestro directorio usamos **git status**