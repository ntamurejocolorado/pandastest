# Sample Exercises for Library Pandas with jupyter
En este proyecto, se ha estudiado la librería de pandas para python.
Para ello, se ha seguido la guía de este [web](https://www.interactivechaos.com/es/manual/tutorial-de-pandas/presentacion). En ella, se explican los conceptos básicos de pandas para trabajar con datos.

Por supuesto, todo esto se puede ampliar con la documentación oficial de pandas.

## Introducción
Para este proyecto, se trabajará con un entorno tox y con jupyter. Por tanto, para poner en marcha el proyecto, debes seguir los siguientes pasos una vez te hayas descargado.

### Pasos
1. Descargar el proyecto de git.
2. Acceder a la carpeta sample_pandas.
3. Crear el entorno: make env-compile.
4. Crear entorno tox: make env-create.
5. Acceder al entorno: source ./.tox/pandatest/bin/activate

Para comprobar que estamos dentro del entorno podemos escribir python y ver que versión tenemos.
El entorno tox trabaja con la versión 3.7 mientras que en mi caso fuera tengo la versión 3.8.

A continuación, entramos en la carpeta examples, donde tenemos todos los proyectos de cada ejercicio de pandas. Para poder lanzar el entorno de jupyter, escribimos: jupyter notebook nombre.ipynb

[Ayuda Jupyter](https://jupyter.readthedocs.io/en/latest/running.html)
