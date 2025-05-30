# Comandos útiles de Git

1. PRIMER COMMIT

git init

git branch -M main

git add .

git commit -m '_Initial commit_'

git remote add origin <*https://_________________*>

git push -u origin main

2. COMMITS DE PRODUCCION

git add .

git commit -m '_Nombre descriptivo_'

git push

git checkout -- .
_(volver al estado del ultimo commit)_

git checkout -b '_rama-nombre_'
_(crear nueva rama desde ultimo commit)_

git checkout main
_(vuelve a rama main)_

git merge rama-nombres
_(unifica ramas)_

git branch
_(consulta ramas existentes)_

git branch -d rama-nombres
_(elimina rama ya no utilizada, mergeadas con main)_
