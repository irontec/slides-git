### Traer cambios de un remote (I)

* **fetch** nos trae los cambios del repositorio remoto
  * Sólo los descarga, no los aplica sobre la rama en la que estamos
    * Útil para tener nuestra copia del repositorio actualizada
  * Si no indicamos el remote, por defecto es **origin**
```shell
$ git fetch
remote: Counting objects: 79, done.
remote: Compressing objects: 100% (35/35), done.
remote: Total 79 (delta 57), reused 58 (delta 43), pack-reused 1
Unpacking objects: 100% (79/79), done.
From https://github.com/libretro/RetroArch
   1657b9b7c4..e98b165761  master        -> origin/master
   a18e7767f3..6ee8f681da  coverity_scan -> origin/coverity_scan
```
