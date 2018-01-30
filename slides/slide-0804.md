### Traer cambios de un remote (II)

* **pull** nos trae los cambios del repositorio remoto y los aplica
  * Hace una combinación de **[fetch](#/8/3)** y **[merge](#/14)**
    * Si hemos realizado modificaciones previas, podría existir un **[conflicto](#/15)**

```shell
$ git pull
Updating 620c904..d122df9
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)
```
