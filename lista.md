# Comandos necesarios para Git

1. git init 
2. # Inicia un archivo git vacio
3. git add .
4. # Añade todos los archivos que se han actualizado
5. git reset . 
6. # Revierte el cambio en caso de solo quere añadir archivos especificos
7. git add archivo.py 
8. # Añade solo un archivo especifico sin necesidad de usar todos
9. git commit -m "" 
10. # Crea un commit para comentar los cambios realizados
11. git checkout -- . 
12. # Vuelve al ultimo commit realizado 
13. git log 
14. # Visualiza todos los commits
15. git commit --amend 
16. # Arregla el ultimo commit y editarlo correctamente
17. git checkout -b nombreRama 
18. # Crea una nueva rama 
19. git branch 
20. # Visualiza la rama en la que te encuentras
21. git checkout nombre 
22. # Esto te posiciona en donde indiques, ya sea en master o el nombre de tu rama
23. git merge nombreRama 
24. # Fusiona los cambios que tengas en una rama para agregarlos a la master
25. git branch -d nombreRama 
26. # Elimina una rama que ya no necesites
27. git push 
28. # Sube los cambios realizados ya sea a una rama o main
29. git commit -am "mensaje"
30. # Usa -am para no escribir add.