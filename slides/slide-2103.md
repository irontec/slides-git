### Configuración

* Muchas opciones de configuración
  * La plantilla de todas ellas [aquí](https://gitlab.com/gitlab-org/omnibus-gitlab/blob/master/files/gitlab-config-template/gitlab.rb.template)
* El fichero para la configuración del arranque está **/etc/gitlab/gitlab.rb**
  * Es el fichero base del que se genera en base a una plantilla
  * Para regenerar el fichero real hay que ejecutar


```shell
$ gitlab-ctl reconfigure

$ gitlab-ctl restart
```

* Existen otras opciones de configuración que pueden realizarse desde el area de administración
