### ¿Cuándo?

* Siempre que hagamos un **clone** de un repositorio, tendremos un "remote"

```shell
$ git clone https://github.com/git/git.git
...
$ git remote
origin

$ git remote show origin
* remote origin
  Fetch URL: https://github.com/git/git.git
  Push  URL: https://github.com/git/git.git
  ...
  HEAD branch: master
  Remote branch:
    master tracked
  Local branch configured for 'git pull':
    master merges with remote master
  Local ref configured for 'git push':
    master pushes to master (up to date)

```
* "origin" es el nombre por defecto del "remote"/origen de nuestro código clonado
