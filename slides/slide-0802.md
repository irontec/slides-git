### Pero, ¿qué es un remote?
* Es un repositorio remoto de código contra el que podemos trabajar
  * Traernos cambios
  * Enviar cambios
* Podemos tener más de un remote
  * Eso significa que podemos trabajar con/contra más de un repositorio remoto a la vez
* Añadir un remote nuevo:

```shell
$ git remote add git2 https://git.kernel.org/pub/scm/git/git.git

$ git remote -v show
git2	https://git.kernel.org/pub/scm/git/git.git (fetch)
git2	https://git.kernel.org/pub/scm/git/git.git (push)
origin	https://github.com/git/git.git (fetch)
origin	https://github.com/git/git.git (push)
```
