### Global
* **Identificarte**: para que aparezca quién ha realizado los commits
```shell
$ git config --global user.name "Ruben Gómez"
$ git config --global user.email ruben@irontec.com
```
* **Editor**: para forzar el editor que queremos que se abra al hacer un commit
```shell
$ git config --global core.editor vim
```
* **Excluir ficheros**: tipo de ficheros que se van a excluir
```shell
$ git config --global core.excludesfile ~/.gitignore_global
```
