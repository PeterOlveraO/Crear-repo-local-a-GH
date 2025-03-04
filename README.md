##Pasos para crear un repositorio local para despues subirlo a github
1-
cd ~/GitHub - ir a la ruta
2-
mkdir Nombre-de-la-carpeta - crear carpeta
3-
git init - crear el repo local
4-
echo "#Cualquier cosa para el readme" > README.md - crear el archivo readme
5-
git add README.md - agregar archuvo nuevo al repo
6-
git commit -am "mensaje" - hacer el cambio
7-
Abrir githubdesktop y seleccionar el repositorio local que cree osea la carpeta donde hice el init y pushearlo y sha
8-
git remote -v - para verificar la conexion del repo local a github
9-
git branch - para ver como se llama la rama principal

##Pasos para commitear y agregar archivos y etceterrararar

1- Entrar al proyecto a commitear
git add . → Agrega todos los archivos modificados y nuevos.
git add -u → Agrega solo archivos modificados y eliminados, no los nuevos.
git add *.txt → Agrega solo archivos específicos por tipo.
git add carpeta/ → Agrega todos los archivos dentro de una carpeta específica.

despues git commit -am"Descripcion"
git push origin "Nombre de la rama"
