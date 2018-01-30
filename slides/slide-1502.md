* Los ficheros con conflictos aparecen en **Unmerged paths**
  * Git les añade *marcas de conflicto* para que podamos ver donde existe el problema
```shell
<<<<<<< HEAD:index.html
<div id="footer">contact : email.support@github.com</div>
=======
<div id="footer">
 please contact us at support@github.com
</div>
>>>>>>> iss53:index.html
```
* Tenemos dos opciones
  * Solventar el conflicto
  * Deshacer el merge y esperar a que alguien lo haga por nosotros
