* **Fast-forward**: Como **C4** está por delante de **C2**, Git simplete mueve el puntero a la posición de C4
  * Cuando se hace merge de un commit al que se puede llegar de manera "lineal", Git simplemente actualiza el puntero
* Ahora podríamos borrar la rama *hotfix*
```shell
$ git branch -d hotfix
Deleted branch hotfix (3a0874c).
```
* Esta manera de trabajar puede ser la habitual al trabajar una única persona en un repositorio
