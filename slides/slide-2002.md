### Modificar último commit

* Si se nos ha olvidado algo en el último commit podemos solventarlo:
```shell
$ git commit -m 'último commit'
$ git add fichero_olvidado
$ git commit --amend
```
* Podemos añadir a *"último commit"*  ficheros/modificaciones del **staging area** que no habíamos añadido
  * El segundo commit se integra con el anterior
