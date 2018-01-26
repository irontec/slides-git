### Flujo de trabajo (II)

* Volvemos a la rama master y realizamos un cambio rápido

```shell
$ git checkout master
Switched to branch 'master'

$ git checkout -b hotfix
Switched to a new branch 'hotfix'
$ vim index.html
$ git commit -a -m 'fixed the broken email address'
[hotfix 1fb7853] fixed the broken email address
 1 file changed, 2 insertions(+)
```
![asd](./resources/basic-branching-4.png)<!-- .element height="60%" width="60%" -->
