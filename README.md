# demo-repo

testing github setup

Update test

## git commands

clone // copia repositorio a local

ls -la //muestra archivos ocultos

git status

git add . //trackea docs, incluye todos los documentos

git add index.html // trackea solo el doc seleccionado

git commit -m "mensaje sobre la actualización realizada"

///generar ssh key
ssh-keygen -t rsa -b 4096 -C "nahueluboldi@gmail.com"

-> https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

git push origin master
git push origin HEAD:master

## crear repositorio desde local

git init
git add .
git commit -m "descripcion" -m "descripción 2"
git remote add origin https://github... etc // hay que crear el respositorio en github y ahí te da la dirección

git remote -v // para comprobar que se creo correctamente

git push origin -u origin master // para no tener que escribir origin master cada vez

## git branching

git branch // te dice en qué branch estás
git checkout // switch between branches
git checkout -b feature // create a new branch
git diff feature // muestra diferencias entre los archivos de los branches
git merge feature // merge branches
hay que aceptar merge en github
git pull // para actualizar merge en master branch
git branch -d feature // delete branch
