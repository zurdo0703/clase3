.git

1. Istalar Git se descarga desde https://git-scm.com/
2. Ingresar al Git bash
3. Primer comando pwd es como decir dir en cmd
4. Ingresar a una carpeta cd desktop
5. ls me muestra el dir en cmd

6. git init inizializa el repositorio
7. git status muestra el estatus de la carpeta 
8. git add adiciona los archivos a la carpeta .git que esta oculta
9. git add . sube todo en proyecto a git
10. git config --global user.name "zurdo0703" es conextarme al la cuenta 
11. git config --global user.email "edwinrios@hotmail.com"
12. git commit :wq guarda en el servidor
13. git remote add origin https://github.com/zurdo0703/clase3.git sube el repositorio
13.1. git commit -m "actualizacion el txt"
14. git push -u origin master
15. recuperar un archivo git clone https://github.com/zurdo0703/clase3.git


Recomendaciones cmder http://cmder.net/

Manejo de ramas 

git  branch chat Crea una rama
git checkout chat Ingreso a la rama
git merge chat Sube la nueva funcionalidad al master donde chat es la copia que se esta asegurando la funcionalidad

git  branch -d chat elimina la rama creada

ssh-keygen -t rsa -b 4096 -C "edwinrios@hotmail.com" Crea una llave ssh

