### Deshacer modificación de un fichero

* Podemos deshacer las modificaciones de un fichero de area de trabajo
```shell
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

    modified:   CONTRIBUTING.md
```
* Deshacemos los cambios
```shell
$ git checkout -- CONTRIBUTING.md
$ git status
On branch master
nothing to commit, working tree clean
```
