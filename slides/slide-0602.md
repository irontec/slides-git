### Clonar repositorio

* **Clonar**: realizar copia completa del histórico de un repositorio remoto en local
 * **remoto**: GIT soporta distintos protocolos "*remotos*"
   * **local**: está en otro directorio de mi equipo **file://**
   * **http**: accesible por HTTP o HTTPS **https://**
   * **ssh**: accesible por SSH: **ssh://** o **user@server:/...**

```shell
$ git clone https://github.com/git/git.git

Cloning into 'git'...
remote: Counting objects: 236656, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 236656 (delta 0), reused 0 (delta 0), pack-reused 236654
Receiving objects: 100% (236656/236656), 98.17 MiB | 1.63 MiB/s, done.
Resolving deltas: 100% (174365/174365), done.
```
