# Comando útiles de Git

https://www.youtube.com/watch?v=iT4UOkyI09k

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
_permite volver al estado del ultimo commit_

git checkout -b '_rama-nombre_'
_crea nueva rama desde ultimo commit_

git checkout main
_vuelve a rama main_

git merge rama-nombres
_unifica ramas_

git branch
_consulta ramas existentes_

git branch -d rama-nombres
_elimina rama ya no utilizada, ya mergeada con main_
