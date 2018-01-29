### Fichero .submodules
* Contiene la información de los submodules del proyecto
```shell
[submodule "DbConnector"]
	path = DbConnector
	url = https://github.com/chaconinc/DbConnector
```
* Tiene que estar versionado junto con el resto del proyecto
```shell
$ git commit -am 'added DbConnector module'
[master fb9093c] added DbConnector module
 2 files changed, 4 insertions(+)
 create mode 100644 .gitmodules
 create mode 160000 DbConnector
```
* No se hace commit del contenido del directorio *DbConnector*
  * Modo especial (**160000**) el directorio
