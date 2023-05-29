 # Comandos Git

 ### 1.- Working directory | Work tree
 ### 2.- Staging area (index)
 ### 3.- Repository

### git status (verifica los archivos en que are se encuentran)
### git log (verifica los commits hechos)
### git show (muestra las lienas del archivo seleccionado)

## GIT ADD
### 1.- git init (inizializa un repositorio local vacio)
### 2.- git add "nombre.tal" (agrega al staging area el archivo seleccionado)
### 2.1 git add *.html (agrega al staging area todos los archivos con esa extension)
### 2.2 git add /css (agrega al staging area todos los archivos de esa carpeta)
### 2.3 git add . (agrega al staging area todos los archivos, carpetas y subcarpetas)

## GIT COMMIT
### 3.- git commit -m "Mensaje" (agrega todo que esta en Staging area a Repository)

## GIT BRANCH
### 4.- git branch "nombre_rama" (crea una rama con todos los archivos de la rama master)

### 4.1 git brach (Lista todas las ramas)
### 4.2 git checkout "nombre_rama" (Sirve para cambiar de rama)
### 4.3 git checkout -b "nombre_rama" (te posiciona en a rama creada)

### 5.- git merge "nombre_rama" (1.- nos situamos en la rama que queremos dejar los cambios y se lege el nombre de la rama con la que queremos unirla)

## GIT REMOTE
### 6.- git remote add origin "https://github.com/"
### 6.1.- git remote rm origin (Sirve para eliminar el remoto)
### 6.2.- git remote -v (muestra la url del rep al que apunta)

## GIT PUSH
### 7.- git push origin main (manda al repisitorio remoto lo que se tiene en la rama master local)
### 7.1 .- git push --all (sincroniza las ramas locales con el repo remoto)

## GIT CLONE
## 8.- git clone "url" (clona en tu maquina el repo remoto)