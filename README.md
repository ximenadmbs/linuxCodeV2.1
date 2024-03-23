# linuxCodeV2.1
linuxCodeV2.1 carpeta dos
# Comandos terminal git modificaciones posteriores, respaldo github:

https://github.com/ximenadmbs/linuxCodeV2.1.git

### …or create a new repository on the command line

echo "# linuxCodeV2.1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ximenadmbs/linuxCodeV2.1.git
git push -u origin main

###…or push an existing repository from the command line

git remote add origin https://github.com/ximenadmbs/linuxCodeV2.1.git
git branch -M main
git push -u origin main

###…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

### Crear nueva carpeta como repositorio en secuencia:

	git init
	git status
	git add .
	git commit -m

### Agregar todo en la carpeta actual:
   
    git add .

### Agregamos archivo para respaldo con:
    
    git add archivo.mod

### Revisamos el status de los archivos
    
    git status -s

### Realimentaremos en el comentamos de las modificaciones realisadas con:
    
    git commit -m "Se modifico"

### Subir el o los archivos al repositorio de github
    
    git push
