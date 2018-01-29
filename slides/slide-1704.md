### Clonando repositorio con submodules (I)

* Por defecto, al hacer un clone, los submodules no son descargados
  * Los directorios necesarios son creados, pero sin contenido
  * Hay que descargar los submodulos

```shell
$ git submodule init
Submodule 'DbConnector' (https://github.com/example/DbConnector) registered for path 'DbConnector'

$ git submodule update
Cloning into 'DbConnector'...
remote: Counting objects: 11, done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 11 (delta 0), reused 11 (delta 0)
Unpacking objects: 100% (11/11), done.
Checking connectivity... done.
Submodule path 'DbConnector': checked out 'c3f01dc8862123d317dd46284b05b6892c7b29bc'
```
* Ahora el directorio *DbConnector* ya tiene el contenido de su propio repositorio
