### ¿Cómo se hace?
* Necesitamos conocer el hash del commit, tag o rama al que queremos ir
  * Lo podemos ver con la opción **log**
  * Por defecto nos crea un espacio de trabajo "aislado"

```shell
$ git checkout e7e80778e
Note : checking out 'e7e80778e'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at e7e80778e... Merge branch 'nd/add-i-ignore-submodules'
```
