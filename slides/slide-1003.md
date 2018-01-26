### Tags anotados
* Creamos un tag "v1.1" con una nota de información sobre la versión
```shell
$ git tag -a v1.1 -m "v1.1: nueva experiencia de usuario"
```

* Y vemos la información del mismo

```shell
$ git show v1.1
tag v1.1
Tagger: Ruben Gomez Olivencia <ruben@irontec.com>
Date:   Thu Jan 25 17:39:27 2018 +0100

v1.1: nueva experiencia de usuario

commit c35de5306e1547f5834caa5c15379fee7a4047cf (HEAD -> master, tag: v1.1)
Author: Ruben Gomez Olivencia <ruben@irontec.com>
Date:   Thu Jan 25 17:39:07 2018 +0100

    Terminada la nueva experiencia de usuario

...
```
