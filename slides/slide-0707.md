### Buenas costumbres

* Cada commit debería ser "atómico"
  * Sólo debería contener cambios relacionados
  * No deberían ir en el mismo commits ficheros que no tienen nada que ver entre si
    * Se pueden hacer commits de sólo un fichero
    ```shell
    $ git commit fichero0.txt
    ```
  * Esto facilita poder hacer un rollback de manera más sencilla
* Indicar qué se ha hecho en el asunto del commit:
  * BUGFIX, ADDON, FEATURE,...
* Sólo código testado y funcional
