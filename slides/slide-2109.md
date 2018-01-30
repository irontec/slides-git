### Ejemplo (sencillo) de despliegue para pages

* El fichero encargado de ello es: **.gitlab-ci.yml**
  * [Documentación completa](https://docs.gitlab.com/ce/ci/yaml/README.html)
* El ejemplo realiza un despliegue en Docker:
  * Sirve para generar documentación con [mkdocs](http://www.mkdocs.org/)
  * Lo generado se mueve a las **pages** del proyecto

```yaml
image: alpine

pages:
  script:
  - apk --no-cache add py2-pip python-dev
  - pip install mkdocs
  - pip install markdown-include
  - mkdocs build
  - mv site/ public/
  artifacts:
    paths:
    - public
  only:
  - master

```
