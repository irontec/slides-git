* Es posible que al hacer merge se genere un **conflicto**
  * Si se han modificado las mismas partes de código en ambas ramas, Git no sabe cual es el código que tiene preferencia

```shell
$ git merge iss53
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.
```
* Git no genera el **merge commit** y deja el proceso en pausa hasta que resolvamos el conflicto

```shell
$ git status
On branch master
You have unmerged paths.
  (fix conflicts and run "git commit")

Unmerged paths:
  (use "git add <file>..." to mark resolution)

    both modified:      index.html

no changes added to commit (use "git add" and/or "git commit -a")
```
