# docker-sphinx
Sphinx documentation toolchain, latex dependencies and pandoc in an Ubuntu docker container.

Inspired by [docker-asciidoctor](https://github.com/asciidoctor/docker-asciidoctor).

## How to Use it

    docker run -it -v <your directory>:/documents/ plaindocs/docker-sphinx

Use `sphinx-quickstart` to create a new Sphinx project, and the auto generated `Makefile` in an existing project. 
