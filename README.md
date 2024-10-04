# Lista de comandos

1. git init 
   # Inicia un archivo git vacio
2. git add .
   # Añade todos los archivos que se han actualizado
3. git reset . 
   # Revierte el cambio en caso de solo quere añadir archivos especificos
4. git add archivo.py 
   # Añade solo un archivo especifico sin necesidad de usar todos
5. git commit -m "" 
   # Crea un commit para comentar los cambios realizados
7.  git checkout -- . 
   # Vuelve al ultimo commit realizado 
9.  git log 
   # Visualiza todos los commits
11. git commit --amend 
   # Arregla el ultimo commit y editarlo correctamente
13. git checkout -b nombreRama 
   # Crea una nueva rama 
15. git branch 
   # Visualiza la rama en la que te encuentras
17. git checkout nombre 
   # Esto te posiciona en donde indiques, ya sea en master o el nombre de tu rama
19. git merge nombreRama 
   # Fusiona los cambios que tengas en una rama para agregarlos a la master
21. git branch -d nombreRama 
   # Elimina una rama que ya no necesites
23. git push 
   # Sube los cambios realizados ya sea a una rama o main
25. git commit -am "mensaje"
   # Usa -am para no escribir add.