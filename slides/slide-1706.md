### Especificar commit concreto en un Submodule
* Por defecto, al añadir un submodule, se hace referencia al último commit del repositorio
  * Lo ideal es modificarlo para ir a un tag o rama concreto
    * Nos aseguramos que no usamos una rama de desarrollo con errores


```shell
$ cd DbConnector
$ git checkout -b v1.0 v1.0
Previous HEAD position was 5b3ceb8... Merge pull request #228 from ...
Switched to a new branch 'v1.0'

$ git commit -a
$ git show HEAD

diff --git a/DbConnector b/DbConnector
index c3f01dc..af08536 160000
--- a/DbConnector
+++ b/DbConnector
@@ -1 +1 @@
-Subproject commit c3f01dc8862123d317dd46284b05b6892c7b29bc
+Subproject commit af08536772e34f6ef95870bb4cfd85d09bf1c932
```
