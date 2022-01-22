# utilidades
Son utilidades varias

1 Para subir archivos grandes a github, de mas de 100MB, es necesario la utilidad de git: git lfs
https://git-lfs.github.com/

Ejecutar en la carpeta del repo:
  git lfs track "*.zip"

El anterior comando sirve para decir la extension de los archivos que se van a subir con lfs
esto genera un archivo llamado .gitattributes en la ruta que te encuentras y luego para subir el archivo:
  
  git add file.zip
  
  git commit -m "comment"
  
  git push origin nombreRamaEnGit
  
Con esto ya debería haberse subido.

