# Introducción a Python

Este repositorio contiene material práctico para la introducción a la programación en Python. El material está enfocado a quienes tienen conocimiento de programación y necesitan partir con la programación en este lenguaje. Aunque describe brevemente algunos conceptos usados en programación, no es un curso de introducción a la programación.

# Notas de instalación
Antes de comenzar con el tutorial es necesario tener instalado el interprete Python 3.11 o superior (recomendamos Python 3.11 LTS). El que puede ser descargado desde:

- [Python.org](https://www.python.org)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

La forma más fácil es instalar Python es usando `miniconda` y el gestor de paquetes `conda`. Por defecto, `miniconda` instalará una versión de Python definida en la versión del instalador. Sin embargo, es posible instalar otras versiones y las dependencias a través de ambientes virtuales.

Una vez instalado `miniconda` podemos crear un ambiente de trabajo de la siguiente manera:

```shell
$ conda create -n py311 python=3.11
$ conda activate py311
```

## Gestión de dependencias con Poetry (Recomendado)

Para proyectos más complejos, recomendamos usar [Poetry](https://python-poetry.org/) para la gestión de dependencias. La instalación recomendada es mediante [pipx](https://pipx.pypa.io/stable/installation/):

### Instalación de pipx

**En macOS:**
```shell
$ brew install pipx
$ pipx ensurepath
```

**En Linux (Ubuntu 23.04+):**
```shell
$ sudo apt update
$ sudo apt install pipx
$ pipx ensurepath
```

**En Linux (Fedora):**
```shell
$ sudo dnf install pipx
$ pipx ensurepath
```

**En Linux (otras distribuciones):**
```shell
$ python3 -m pip install --user pipx
$ python3 -m pipx ensurepath
```

**En Windows:**
```shell
# Con Scoop
$ scoop install pipx
$ pipx ensurepath

# Con pip
$ py -m pip install --user pipx
$ .\pipx.exe ensurepath
```

### Instalación de Poetry

Una vez instalado pipx:
```shell
# Instalar Poetry con pipx
$ pipx install poetry

# Inicializar un proyecto
$ poetry init
$ poetry install
```

En Windows es necesario verificar que el directorio de Python esté incluido en el path de las variables de entorno.

# Herramientas de desarrollo
Python es un lenguaje interpretado que permite ejecutar las sentencias directamente desde una consola o terminal. Sin embargo, para programar es recomendable utilizar un IDE para facilitar el desarrollo, la búsqueda de errores y depuración, mantenimiento del código, entre otras actividades propias del desarrollo de software. Python tiene un editor básico llamado IDLE. Existen otros IDEs con mayores prestaciones y compatibles con Python. A continuación dejo un listado con ellos:

## IDEs Recomendados
- [Visual Studio Code](https://code.visualstudio.com/) - Editor gratuito con excelente soporte para Python
- [PyCharm](https://www.jetbrains.com/es-es/pycharm/) Community Edition - IDE completo para Python
- [JupyterLab](https://jupyter.org/) - Entorno interactivo para notebooks (recomendado para este curso)
- [Jupyter Notebook](https://jupyter.org/) - Versión clásica de Jupyter
- [GitHub Codespaces](https://github.com/features/codespaces) - Entorno de desarrollo en la nube

## Editores de Texto
- [Vim](https://www.vim.org/) - Editor de texto en terminal
- [Neovim](https://neovim.io/) - Fork moderno de Vim

# Buenas Prácticas de Desarrollo

## Ambientes Virtuales
Siempre es recomendable trabajar con ambientes virtuales para aislar las dependencias de cada proyecto:

```shell
# Con venv (incluido en Python)
$ python -m venv mi_proyecto
$ source mi_proyecto/bin/activate  # Linux/Mac
$ mi_proyecto\Scripts\activate     # Windows

# Con conda
$ conda create -n mi_proyecto python=3.11
$ conda activate mi_proyecto
```

## Control de Versiones con Git
Git es esencial para el desarrollo de software:

```shell
$ git init
$ git add .
$ git commit -m "Mensaje descriptivo"
$ git push origin main
```

## Herramientas de Calidad de Código
- **Linting**: [flake8](https://flake8.pycqa.org/) o [pylint](https://pylint.org/)
- **Formateo**: [black](https://black.readthedocs.io/) o [autopep8](https://pypi.org/project/autopep8/)
- **Testing**: [pytest](https://pytest.org/) para pruebas unitarias

## Estilo de Código
Seguir [PEP 8](https://pep8.org/) - Guía de estilo oficial de Python.

# Recursos Externos
Al igual que en matemáticas u otra materia, programar require de práctica. A continuación dejo algunos sitios y lecturas que podrían ser útiles para el aprendizaje y práctica de programación en Python.

- [HackerRank](http://www.hackerrank.com): plataforma web de reclutamiento de fuerza laboral en áreas de tecnología. Puede ser utilizada también para el aprendizaje y práctica de programación.

- [Codecademy](https://www.codecademy.com/): plataforma web orientada a la educación y promoción del aprendizaje de diferentes áreas de la computación como programación, ciencia de datos y desarrollo web.

- [Codility](https://app.codility.com/programmers/): Codility es una plataforma para evaluar candidatos a puestos de desarrollo. Tiene una sección para práctica con temas y preguntas similares a las que podrían aparecen en los test de código.

- [LeetCode](https://leetcode.com/): plataforma para mejorar habilidades en programación y preparación para entrevistas técnicas.

- [AlgoExpert](https://www.algoexpert.io/): plataforma para mejorar habilidades en programación y preparación para entrevistas técnicas.

# Feedback
Por favor sientanse libres de dejar comentarios, sugerencias u observaciones en la sección de [Issues](https://github.com/cpieringer/intro_python/issues) de este repositorio.
