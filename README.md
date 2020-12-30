# Introducción a Python

*Christian Pieringer*
- email: cpieringer@uc.cl
- github: [cpieringer](https://github.com/cpieringer)

Este repositorio contiene material práctico para la introducción a la a programación en Python. El material está enfocado a quienes tienen conocimiento de programación y necestian partir con la programación en este lenguaje. Aun cuando describe brevemente algunos conceptos usados en programación, no es un curso de introducción a la programación.

# Notas de instalación
Antes de comenzar con el tutorial es necesario tener instalado el interprete Python 3.7. el que puede ser descargado desde:

- [Python.org](www.python.org)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

La forma más fácil es instalar Python es usando `miniconda` y el gestor de paquetes `conda`. Por defecto, `miniconda` instalará una versión de Python definida en la versión del instalador. Sin embargo, es posible instalar otras versiones y las dependencias a través de ambientes virtuales.

Una vez instalado `miniconda` podemos crear un ambiente de trabajo de la siguiente manera:

```shell
$ conda create -n py38 python=3.8
$ conda activate py38
```

En Windows es necesario verificar que el directorio de Python esté incluido en el path de las variables de entorno.

# Herramientas de desarrollo
Python es un lenguaje interpretado que permite ejecutar las sentencias directamente desde una consola o terminal. Sin embargo, para programar es recomendable utilizar un IDE para facilitar el desarrollo, la búsqueda de errores y depuración, mantenimiento del código, entre otras actividades propias del desarrollo de software. Python tiene un editor básico llamado IDLE. Existen otros IDEs con mayores prestaciones y compatilibles con Python. A continuación dejo un listado con ellos:

- [PyCharm](https://www.jetbrains.com/es-es/pycharm/) Community Edition
- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
- [Jupyter Notebook](https://jupyter.org/)
- [Vim](https://www.vim.org/)


# Recursos Externos
Al igual que en matemáticas u otra materia, programar require de práctica. A continuación dejo algunos sitios y lecturas que podrían ser útiles para el aprendizaje y práctica de programación en Python.

- [HackerRank](http://www.hackerrank.com): plataforma web de reclutamiento de fuerza laboral en áreas de tecnología. Puede ser utilizada también para el aprendizaje y práctica de programación.

- [Codecademy](https://www.codecademy.com/): plataforma web orientada a la educación y promoción del aprendizaje de diferentes áreas de la computación como programación, ciencia de datos y desarrollo web.

- [Codility](https://app.codility.com/programmers/): Codility es una plataforma para evaluar candidatos a puestos de desarrollo. Tiene una sección para práctica con temas y preguntas similares a las que podrían aparecen en los test de código.

- [LeetCode](https://leetcode.com/): plataforma para mejorar habilidades en programación y preparación para entrevistas técnicas.

- [AlgoExpert](https://www.algoexpert.io/): plataforma para mejorar habilidades en programación y preparación para entrevistas técnicas.

# Feedback
Por favor sientanse libres de dejar comentarios, sugerencias u observaciones en la sección de [Issues](https://github.com/cpieringer/intro_python/issues) de este repositorio.
