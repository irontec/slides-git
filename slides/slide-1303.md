## ¿Cómo se crean?

* Estando en el commit desde el que queremos diverger
```shell
$ git branch testing
```
* Crear la rama y movernos a ella
```shell
$ git checkout -b testing2
```
* Partiendo de un commit/tag concreto:
```shell
$ git checkout e7e80778e -b prueba
```
* Hacer cambio de una rama a otra

```shell
$ git checkout master

$ git checkout prueba
```
