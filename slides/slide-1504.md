### Deshacer el merge
* Existe la posibilidad de que no sepamos solventar el merge, por lo que podemos abortarlo
  * Alguien con más conocimientos de los ficheros en conflicto debería encargarse de hacer el merge


```
$ git status -sb
## master
UU index.html

$ git merge --abort

$ git status -sb
## master
```
* **UU**: unmerged, both modified
