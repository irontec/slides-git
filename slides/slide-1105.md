### Ejemplo
* Excluímos de manera global en nuestra configuración:
```shell
$ cat ~/.gitignore_global
*~
.*.swp
.DS_Store
```
* Para un repositorio concreto
  * fichero **.gitignore** dentro del repositorio
```shell
$ cat .gitignore
*.tar.gz
*.dsc
*.deb
*.exe
cache/*
tmp/*
...
```
