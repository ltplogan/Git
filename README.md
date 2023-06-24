# Prácticas Git y Github
## Comandos

```sh
$ git add 
$ git status
$ git commit 
$ git log 
$ git diff
```
* Añade contenido del directorio de trabajo al área de ensayo (staging area o 'index') para la próxima confirmación.
* Te mostrará los diferentes estados de los archivos en tu directorio de trabajo y área de ensayo.
* Toma todos los contenidos de los archivos a los que se les realiza el seguimiento con git add y registra una nueva instantánea permanente en la base de datos y luego avanza el puntero de la rama en la rama actual.
* Historico de los commit que hemos hecho.
* Puedo ver una lista de cambios que he hecho en mis archivos y que no están todavía en el staged (es un área temporal en la que se guardan cambios que le he dicho con **add**).

## Cómo deshacer una modificación
Si es el último cambio y nos hemos olvidado de algo podemos volver atrás con el comando **git commit --amend**.
**git checkout** -- index.html descarta cambios. Si queremos el archivo como estaba antes. Si hacemos un git add en este caso no podemos hacer un git checkout, en este caso utilizamos **git reset HEAD index.html** para indicarle que quiero resetear un archivo y poder eliminar la última modificación.

## Cómo deshacer un commit










