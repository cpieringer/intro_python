# Introducción a Python

*Christian Pieringer*
- email: cpieringer@inacap.cl
- github: [cpieringer](https://github.com/cpieringer)

Este repositorio contienen el material del taller de introducción a Python.

# Notas de instalación
Antes de comenzar con el tutorial es necesario tener instalado el interprete Python 3.7. el que puede ser descargado desde:

- [Python.org](www.python.org)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

La forma más fácil es instalar Python es usando `miniconda` y el gestor de paquetes `conda`. Por defecto, `miniconda` instalará una versión de Python definida en la versión del instalador. Sin embargo, es posible instalar otras versiones y las dependencias a través de ambientes virtuales.

Una vez instalado `miniconda` podemos crear un ambiente de trabajo de la siguiente manera:

```shell
$ conda create -n py37 python=3.7
$ conda activate py37
```

En Windows es necesario verificar que el directorio de Python esté incluido en el path de las variables de entorno.


