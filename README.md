# docker-sphinx
[Sphinx](http://sphinx-doc.org/) documentation toolchain, latex dependencies and [pandoc](http://johnmacfarlane.net/pandoc) in an Ubuntu docker container.

## How to Use it

    docker run -it -v <your directory>:/documents/ plaindocs/docker-sphinx

Use `sphinx-quickstart` to create a new Sphinx project, and `make` to use the auto generated `Makefile` in an existing project. More info in the [Sphinx tutorial](http://sphinx-doc.org/tutorial.html).

The built container is available at the [Docker Hub](https://registry.hub.docker.com/u/plaindocs/docker-sphinx/).

Inspired by [docker-asciidoctor](https://github.com/asciidoctor/docker-asciidoctor).
