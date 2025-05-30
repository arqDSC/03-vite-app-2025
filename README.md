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

3. VOLVER AL ESTADO DEL ULTIMO COMMIT

git checkout -- . _permite corregir ultimo commit_
git commit --amend _permite corregir ultimo commit_
