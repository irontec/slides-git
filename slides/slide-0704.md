* Qué pasa si volvemos a modificar **fichero0.txt**:


```shell
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

    modified:   fichero0.txt
    new file:   fichero1.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

    modified:   fichero0.txt
```

* ¿El fichero de Schrödinger?
 * ¡Tiene cambios que van a ir en el siguiente commit y otros que no!
   * Es importante entender esto
